# DevKit OLED Canvas

This JS library has the same API interface as DevKit OLED class, see <https://microsoft.github.io/azure-iot-developer-kit/docs/apis/display/>.

```html
<canvas id="oled" width="256" height="128"></canvas>
<script src="oled.js"></script>
<script>
var screen = new Screen(document.getElementById('oled'));
screen.print('IoT DevKit');
screen.print(2, '   Hello World', false);
</script>
```
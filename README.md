# Examples for LVGL

LVGL is a free and open-source graphics library providing everything you need to create a Graphical User Interface (GUI) on embedded systems with easy-to-use graphical elements, beautiful visual effects and low memory footprint.

GitHub: https://github.com/lvgl/lvgl
Website: https://lvgl.io

## Add the examples to your projects
1. Clone this repository: `git clone https://github.com/lvgl/lv_examples.git`.
2. The `lv_examples` directory should be next to the `lvgl` directory in your project.

Similary to `lv_conf.h` there is a configuration file for the examples too. It is called `lv_ex_conf.h`.
1. Copy `lv_examples/lv_ex_conf_templ.h` next to `lv_examples` directory
2. Rename is to `lv_ex_conf.h`
3. Change the first `#if 0` to `#if 1` to enable the file's content
4. Enable or Disable modules


## Content

### Examples

#### Get strated
If you are new to LVGL chcek these example first. They demonstrates the basic mechanizms of the library.
See the [lv_ex_get_started](https://github.com/lvgl/lv_examples/tree/master/src/lv_ex_get_started) folder.
You can also take a lookat the [Quich overview](https://docs.lvgl.io/v7/en/html/get-started/quick-overview.html) of LVGL to learn the besics. 

#### Styles
LVGL has a powerful and versatile style system. These examples show how to use the most common style properties, e.g. styling rectangles, shadows, images, lines, transitions and so on. See the [lv_ex_style](https://github.com/lvgl/lv_examples/tree/master/src/lv_ex_style) folder.
Be sure to read the [Documentation](https://docs.lvgl.io/v7/en/html/overview/style.html) of the styles to fully understand them.

#### Widgets
LVGL has more then 35 widgets and you can find examples for all of them.
Go to the [lv_ex_widgets](https://github.com/lvgl/lv_examples/tree/master/src/lv_ex_widgets) folder to see them.
The documentation of the widgets can be found [here](https://docs.lvgl.io/v7/en/html/widgets/index.html).

### Demos

#### Benchmark
A demo to measure the performance of LVGL or to compare different settings. 
See in [lv_demo_benchmark](https://github.com/lvgl/lv_examples/tree/master/src/lv_demo_benchmark) folder.
<img src="https://github.com/lvgl/lv_examples/blob/master/src/lv_demo_benchmark/screenshot1.png?raw=true" width=600px alt="Benchmark demo with LVGL embedded GUI library">

#### Keypad and encoder
LVGL allows you to control the widgets with keypad and/or encoder without touchpad.
See in [lv_demo_keypad_encoder](https://github.com/lvgl/lv_examples/tree/master/src/lv_demo_keypad_encoder) folder.
<img src="https://github.com/lvgl/lv_examples/blob/master/src/lv_demo_keypad_encoder/screenshot1.gif?raw=true" width=600px alt="Keypad and encoder navigation in LVGL embedded GUI library">

#### Printer
An printer example created with LVGL. This demo is optmized for 800x480 resoltion and among many others it demonstrates custom theme creation, style transitions and animations. 
See in [lv_demo_printer](https://github.com/lvgl/lv_examples/tree/master/src/lv_demo_printer) folder.
<img src="https://github.com/lvgl/lv_examples/blob/master/src/lv_demo_printer/screenshot1.gif?raw=true" width=600px alt="Printer demo with LVGL embedded GUI library">

#### Stress
A stress test for LVGL. It contains a lot of object creation, deletion, animations, styles usage and so on. It can be used if there is any memory curroption during heavy usage or any memory leaks. 
See in [lv_demo_stress](https://github.com/lvgl/lv_examples/tree/master/src/lv_demo_stress) folder.
<img src="https://github.com/lvgl/lv_examples/blob/master/src/lv_demo_stress/screenshot1.gif?raw=true" width=600px alt="Stress tes tfor LVGL">

#### Widgets
Shows how the widgets look like out of the bof using the built-in material theme.  
See in [lv_demo_widgets](https://github.com/lvgl/lv_examples/tree/master/src/lv_demo_widgets) folder.

<img src="https://github.com/lvgl/lv_examples/blob/master/src/lv_demo_widgets/screenshot1.gif?raw=true" width=600px alt="Basic demo to show the widgets of LVGL">

## Contributing
For contribution and coding style guidelines, please refer to the file docs/CONTRIBUTNG.md in the main LVGL repo:
  https://github.com/lvgl/lvgl


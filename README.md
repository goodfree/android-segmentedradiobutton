Segmented Radio Buttons for Android
===================================

这是我实现的iOS的分段控制为Android RadioGroup中延伸和单选按钮。示例项目包括.

Screenshots
-----------

![Segmented Toggle Button](https://github.com/makeramen/android-segmentedradiobutton/raw/master/screens/segmentedradio.png)

Usage
-----

* 仅文本按钮，你只需SegmentedRadioGroup.java的延伸RadioGroup中，因此，所有标准的单选按钮实现回调应该。

* 对于图像按钮，实现代替单选按钮SegmentedRadioImageButton。

* 可绘制都包括在内，但可以很容易地进行更换。

* 例如使用项目

已知问题
------------

* SegmentedRadioImageButton目前使用自定义的实施scaleType到CENTER_INSIDE相似的，不尊重填充值。如果有人想延长OnDraw方法，这样做，那将不胜感激。

*，RadioGroup中有一个错误，当您使用或检查clearCheck（）（）编程调用onCheckedChangedListener多次。 [这]更多信息，（http://stackoverflow.com/questions/4519103/error-in-androids-clearcheck-for-radiogroup）和[这]（https://code.google.com/p/android/issues/detail?id=4785）的一个可能的解决方法吗？.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/vinc3m1/android-segmentedradiobutton/trend.png)](https://bitdeli.com/free "Bitdeli Badge")


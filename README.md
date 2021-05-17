# QtGradientEditor
The Qt Gradient Editor extracted by me from Qt Designer
# Screenshot
![alt text](https://raw.githubusercontent.com/yanis60/QtGradientEditor/main/images/image.png)
# Build
- Copy this project to your main project.
- Add this INCLUDEPATH += "$$PWD\qtgradienteditor" to the .pro file.
# Usage
```
bool ok;
QGradient gradient = QtGradientDialog::getGradient(&ok, QLinearGradient(), this);
if (!ok)
return;
```

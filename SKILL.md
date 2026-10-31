# javafx Skill

Use this skill to work with Norm module `javafx` version 4. Use only declarations listed below.

## `javafx`

Source: `Alert.norm`

### `Alert`

```norm
class Alert extends Dialog<ButtonType> implements EventTarget
```

#### `Alert`

```norm
Alert(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `close`

```norm
Void close()
```

Returns: `Void`

#### `initOwner`

```norm
Void initOwner(Window? arg0)
```

Parameters:

- `arg0`: `Window?`

Returns: `Void`

#### `setContentText`

```norm
Void setContentText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setHeaderText`

```norm
Void setHeaderText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setOnHidden`

```norm
Void setOnHidden(Function<Void(DialogEvent?)>? arg0)
```

Parameters:

- `arg0`: `Function<Void(DialogEvent?)>?`

Returns: `Void`

#### `setTitle`

```norm
Void setTitle(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `show`

```norm
Void show()
```

Returns: `Void`

### `alertNew`

```norm
Alert alertNew(AlertAlertType? arg0)
```

Parameters:

- `arg0`: `AlertAlertType?`

Returns: `Alert`

## `javafx`

Source: `AlertAlertType.norm`

### `AlertAlertType`

```norm
enum AlertAlertType
```

#### `CONFIRMATION`

```norm
CONFIRMATION
```

#### `ERROR`

```norm
ERROR
```

#### `INFORMATION`

```norm
INFORMATION
```

#### `NONE`

```norm
NONE
```

#### `WARNING`

```norm
WARNING
```

## `javafx`

Source: `BooleanProperty.norm`

### `BooleanProperty`

```norm
class BooleanProperty extends ReadOnlyBooleanProperty implements Property<Boolean>, WritableBooleanValue, ReadOnlyProperty<Boolean>, ObservableBooleanValue
```

#### `BooleanProperty`

```norm
BooleanProperty(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx`

Source: `Button.norm`

### `Button`

```norm
class Button extends ButtonBase implements Skinnable, EventTarget, Styleable
```

#### `Button`

```norm
Button(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `fire`

```norm
Void fire()
```

Returns: `Void`

#### `setOnAction`

```norm
Void setOnAction(Function<Void(ActionEvent?)>? arg0)
```

Parameters:

- `arg0`: `Function<Void(ActionEvent?)>?`

Returns: `Void`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

### `buttonNew`

```norm
Button buttonNew()
```

Returns: `Button`

## `javafx`

Source: `CheckBox.norm`

### `CheckBox`

```norm
class CheckBox extends ButtonBase implements Skinnable, EventTarget, Styleable
```

#### `CheckBox`

```norm
CheckBox(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `isSelected`

```norm
Boolean isSelected()
```

Returns: `Boolean`

#### `selectedProperty`

```norm
BooleanProperty? selectedProperty()
```

Returns: `BooleanProperty?`

#### `setMaxWidth`

```norm
Void setMaxWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setSelected`

```norm
Void setSelected(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

### `checkBoxNew`

```norm
CheckBox checkBoxNew()
```

Returns: `CheckBox`

## `javafx`

Source: `Event.norm`

### `Event`

```norm
class Event extends EventObject implements Cloneable, Serializable
```

#### `Event`

```norm
Event(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `consume`

```norm
Void consume()
```

Returns: `Void`

## `javafx`

Source: `EventTarget.norm`

### `EventTarget`

```norm
interface EventTarget
```

## `javafx`

Source: `FXCollections.norm`

### `FXCollections`

```norm
class FXCollections
```

#### `FXCollections`

```norm
FXCollections(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `fxCollectionsObservableArrayList`

```norm
ObservableList<E>? fxCollectionsObservableArrayList<E>()
```

Type parameters:

- `E`

Returns: `ObservableList<E>?`

### `fxCollectionsSort`

```norm
Void fxCollectionsSort<T>(ObservableList<T>? arg0, Function<Integer(T?, T?)>? arg1)
```

Type parameters:

- `T`

Parameters:

- `arg0`: `ObservableList<T>?`
- `arg1`: `Function<Integer(T?, T?)>?`

Returns: `Void`

## `javafx`

Source: `HBox.norm`

### `HBox`

```norm
class HBox extends Pane implements EventTarget, Styleable
```

#### `HBox`

```norm
HBox(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getChildren`

```norm
ObservableList<Node>? getChildren()
```

Returns: `ObservableList<Node>?`

### `hBoxNew`

```norm
HBox hBoxNew(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `HBox`

### `hBoxSetHgrow`

```norm
Void hBoxSetHgrow(Node? arg0, Priority? arg1)
```

Parameters:

- `arg0`: `Node?`
- `arg1`: `Priority?`

Returns: `Void`

## `javafx`

Source: `Image.norm`

### `Image`

```norm
class Image
```

#### `Image`

```norm
Image(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getHeight`

```norm
Double getHeight()
```

Returns: `Double`

#### `getUrl`

```norm
String? getUrl()
```

Returns: `String?`

#### `getWidth`

```norm
Double getWidth()
```

Returns: `Double`

#### `isError`

```norm
Boolean isError()
```

Returns: `Boolean`

### `imageNew`

```norm
Image imageNew(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Image`

## `javafx`

Source: `Insets.norm`

### `Insets`

```norm
class Insets implements Interpolatable<Insets>
```

#### `Insets`

```norm
Insets(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `insetsNew`

```norm
Insets insetsNew(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Insets`

### `insetsNew`

```norm
Insets insetsNew(Double arg0, Double arg1, Double arg2, Double arg3)
```

Parameters:

- `arg0`: `Double`
- `arg1`: `Double`
- `arg2`: `Double`
- `arg3`: `Double`

Returns: `Insets`

## `javafx`

Source: `Label.norm`

### `Label`

```norm
class Label extends Labeled implements Skinnable, EventTarget, Styleable
```

#### `Label`

```norm
Label(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

### `labelNew`

```norm
Label labelNew()
```

Returns: `Label`

## `javafx`

Source: `Labeled.norm`

### `Labeled`

```norm
class Labeled extends Control implements Skinnable, EventTarget, Styleable
```

#### `Labeled`

```norm
Labeled(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getText`

```norm
String? getText()
```

Returns: `String?`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setWrapText`

```norm
Void setWrapText(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

## `javafx`

Source: `Node.norm`

### `Node`

```norm
class Node implements EventTarget, Styleable
```

#### `Node`

```norm
Node(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `applyCss`

```norm
Void applyCss()
```

Returns: `Void`

#### `getId`

```norm
String? getId()
```

Returns: `String?`

#### `getLayoutX`

```norm
Double getLayoutX()
```

Returns: `Double`

#### `getLayoutY`

```norm
Double getLayoutY()
```

Returns: `Double`

#### `getNodeOrientation`

```norm
NodeOrientation? getNodeOrientation()
```

Returns: `NodeOrientation?`

#### `getStyle`

```norm
String? getStyle()
```

Returns: `String?`

#### `getStyleClass`

```norm
ObservableList<String>? getStyleClass()
```

Returns: `ObservableList<String>?`

#### `isDisabled`

```norm
Boolean isDisabled()
```

Returns: `Boolean`

#### `maxHeight`

```norm
Double maxHeight(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Double`

#### `maxWidth`

```norm
Double maxWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Double`

#### `minHeight`

```norm
Double minHeight(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Double`

#### `minWidth`

```norm
Double minWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Double`

#### `prefHeight`

```norm
Double prefHeight(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Double`

#### `prefWidth`

```norm
Double prefWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Double`

#### `requestFocus`

```norm
Void requestFocus()
```

Returns: `Void`

#### `resize`

```norm
Void resize(Double arg0, Double arg1)
```

Parameters:

- `arg0`: `Double`
- `arg1`: `Double`

Returns: `Void`

#### `resizeRelocate`

```norm
Void resizeRelocate(Double arg0, Double arg1, Double arg2, Double arg3)
```

Parameters:

- `arg0`: `Double`
- `arg1`: `Double`
- `arg2`: `Double`
- `arg3`: `Double`

Returns: `Void`

#### `setDisable`

```norm
Void setDisable(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

#### `setId`

```norm
Void setId(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setNodeOrientation`

```norm
Void setNodeOrientation(NodeOrientation? arg0)
```

Parameters:

- `arg0`: `NodeOrientation?`

Returns: `Void`

#### `setStyle`

```norm
Void setStyle(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

## `javafx`

Source: `NodeOrientation.norm`

### `NodeOrientation`

```norm
enum NodeOrientation
```

#### `INHERIT`

```norm
INHERIT
```

#### `LEFT_TO_RIGHT`

```norm
LEFT_TO_RIGHT
```

#### `RIGHT_TO_LEFT`

```norm
RIGHT_TO_LEFT
```

## `javafx`

Source: `Observable.norm`

### `Observable`

```norm
interface Observable
```

#### `addListener`

```norm
Void addListener(Function<Void(Observable?)>? arg0)
```

Parameters:

- `arg0`: `Function<Void(Observable?)>?`

Returns: `Void`

#### `removeListener`

```norm
Void removeListener(Function<Void(Observable?)>? arg0)
```

Parameters:

- `arg0`: `Function<Void(Observable?)>?`

Returns: `Void`

## `javafx`

Source: `ObservableList.norm`

### `ObservableList`

```norm
interface ObservableList<E> extends JavaList<E>, Observable
```

Type parameters:

- `E`

## `javafx`

Source: `ObservableValue.norm`

### `ObservableValue`

```norm
interface ObservableValue<T> extends Observable
```

Type parameters:

- `T`

#### `getValue`

```norm
T? getValue()
```

Returns: `T?`

## `javafx`

Source: `Orientation.norm`

### `Orientation`

```norm
enum Orientation
```

#### `HORIZONTAL`

```norm
HORIZONTAL
```

#### `VERTICAL`

```norm
VERTICAL
```

## `javafx`

Source: `Pane.norm`

### `Pane`

```norm
class Pane extends Region implements EventTarget, Styleable
```

#### `Pane`

```norm
Pane(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getChildren`

```norm
ObservableList<Node>? getChildren()
```

Returns: `ObservableList<Node>?`

## `javafx`

Source: `Parent.norm`

### `Parent`

```norm
class Parent extends Node implements EventTarget, Styleable
```

#### `Parent`

```norm
Parent(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `layout`

```norm
Void layout()
```

Returns: `Void`

## `javafx`

Source: `PasswordField.norm`

### `PasswordField`

```norm
class PasswordField extends TextField implements Skinnable, EventTarget, Styleable
```

#### `PasswordField`

```norm
PasswordField(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getText`

```norm
String? getText()
```

Returns: `String?`

#### `getText`

```norm
String? getText(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `String?`

#### `setPromptText`

```norm
Void setPromptText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `textProperty`

```norm
StringProperty? textProperty()
```

Returns: `StringProperty?`

### `passwordFieldNew`

```norm
PasswordField passwordFieldNew()
```

Returns: `PasswordField`

## `javafx`

Source: `Platform.norm`

### `Platform`

```norm
class Platform
```

#### `Platform`

```norm
Platform(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `platformExit`

```norm
Void platformExit()
```

Returns: `Void`

### `platformIsFxApplicationThread`

```norm
Boolean platformIsFxApplicationThread()
```

Returns: `Boolean`

### `platformRunLater`

```norm
Void platformRunLater(Function<Void()>? arg0)
```

Parameters:

- `arg0`: `Function<Void()>?`

Returns: `Void`

### `platformSetImplicitExit`

```norm
Void platformSetImplicitExit(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

### `platformStartup`

```norm
Void platformStartup(Function<Void()>? arg0)
```

Parameters:

- `arg0`: `Function<Void()>?`

Returns: `Void`

## `javafx`

Source: `Priority.norm`

### `Priority`

```norm
enum Priority
```

#### `ALWAYS`

```norm
ALWAYS
```

#### `NEVER`

```norm
NEVER
```

#### `SOMETIMES`

```norm
SOMETIMES
```

## `javafx`

Source: `Region.norm`

### `Region`

```norm
class Region extends Parent implements EventTarget, Styleable
```

#### `Region`

```norm
Region(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getHeight`

```norm
Double getHeight()
```

Returns: `Double`

#### `getPadding`

```norm
Insets? getPadding()
```

Returns: `Insets?`

#### `getWidth`

```norm
Double getWidth()
```

Returns: `Double`

#### `setMaxHeight`

```norm
Void setMaxHeight(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setMaxWidth`

```norm
Void setMaxWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setMinHeight`

```norm
Void setMinHeight(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setMinWidth`

```norm
Void setMinWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setPadding`

```norm
Void setPadding(Insets? arg0)
```

Parameters:

- `arg0`: `Insets?`

Returns: `Void`

#### `setPrefHeight`

```norm
Void setPrefHeight(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setPrefWidth`

```norm
Void setPrefWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

## `javafx`

Source: `Scene.norm`

### `Scene`

```norm
class Scene implements EventTarget
```

#### `Scene`

```norm
Scene(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getStylesheets`

```norm
ObservableList<String>? getStylesheets()
```

Returns: `ObservableList<String>?`

#### `getWindow`

```norm
Window? getWindow()
```

Returns: `Window?`

### `sceneNew`

```norm
Scene sceneNew(Parent? arg0, Double arg1, Double arg2)
```

Parameters:

- `arg0`: `Parent?`
- `arg1`: `Double`
- `arg2`: `Double`

Returns: `Scene`

## `javafx`

Source: `ScrollPane.norm`

### `ScrollPane`

```norm
class ScrollPane extends Control implements Skinnable, EventTarget, Styleable
```

#### `ScrollPane`

```norm
ScrollPane(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getContent`

```norm
Node? getContent()
```

Returns: `Node?`

#### `getHbarPolicy`

```norm
ScrollPaneScrollBarPolicy? getHbarPolicy()
```

Returns: `ScrollPaneScrollBarPolicy?`

#### `getVbarPolicy`

```norm
ScrollPaneScrollBarPolicy? getVbarPolicy()
```

Returns: `ScrollPaneScrollBarPolicy?`

#### `isFitToHeight`

```norm
Boolean isFitToHeight()
```

Returns: `Boolean`

#### `isFitToWidth`

```norm
Boolean isFitToWidth()
```

Returns: `Boolean`

#### `setContent`

```norm
Void setContent(Node? arg0)
```

Parameters:

- `arg0`: `Node?`

Returns: `Void`

#### `setFitToHeight`

```norm
Void setFitToHeight(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

#### `setFitToWidth`

```norm
Void setFitToWidth(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

#### `setHbarPolicy`

```norm
Void setHbarPolicy(ScrollPaneScrollBarPolicy? arg0)
```

Parameters:

- `arg0`: `ScrollPaneScrollBarPolicy?`

Returns: `Void`

#### `setVbarPolicy`

```norm
Void setVbarPolicy(ScrollPaneScrollBarPolicy? arg0)
```

Parameters:

- `arg0`: `ScrollPaneScrollBarPolicy?`

Returns: `Void`

### `scrollPaneNew`

```norm
ScrollPane scrollPaneNew()
```

Returns: `ScrollPane`

## `javafx`

Source: `ScrollPaneScrollBarPolicy.norm`

### `ScrollPaneScrollBarPolicy`

```norm
enum ScrollPaneScrollBarPolicy
```

#### `ALWAYS`

```norm
ALWAYS
```

#### `AS_NEEDED`

```norm
AS_NEEDED
```

#### `NEVER`

```norm
NEVER
```

## `javafx`

Source: `SingleSelectionModel.norm`

### `SingleSelectionModel`

```norm
class SingleSelectionModel<T> extends SelectionModel<T>
```

Type parameters:

- `T`

#### `SingleSelectionModel`

```norm
SingleSelectionModel(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getSelectedIndex`

```norm
Integer getSelectedIndex()
```

Returns: `Integer`

#### `select`

```norm
Void select(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

#### `selectedIndexProperty`

```norm
ReadOnlyIntegerProperty? selectedIndexProperty()
```

Returns: `ReadOnlyIntegerProperty?`

## `javafx`

Source: `StackPane.norm`

### `StackPane`

```norm
class StackPane extends Pane implements EventTarget, Styleable
```

#### `StackPane`

```norm
StackPane(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getChildren`

```norm
ObservableList<Node>? getChildren()
```

Returns: `ObservableList<Node>?`

#### `setPadding`

```norm
Void setPadding(Insets? arg0)
```

Parameters:

- `arg0`: `Insets?`

Returns: `Void`

### `stackPaneNew`

```norm
StackPane stackPaneNew()
```

Returns: `StackPane`

## `javafx`

Source: `Stage.norm`

### `Stage`

```norm
class Stage extends Window implements EventTarget
```

#### `Stage`

```norm
Stage(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `close`

```norm
Void close()
```

Returns: `Void`

#### `getIcons`

```norm
ObservableList<Image>? getIcons()
```

Returns: `ObservableList<Image>?`

#### `hide`

```norm
Void hide()
```

Returns: `Void`

#### `setIconified`

```norm
Void setIconified(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

#### `setMinHeight`

```norm
Void setMinHeight(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setMinWidth`

```norm
Void setMinWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setOnCloseRequest`

```norm
Void setOnCloseRequest(Function<Void(WindowEvent?)>? arg0)
```

Parameters:

- `arg0`: `Function<Void(WindowEvent?)>?`

Returns: `Void`

#### `setScene`

```norm
Void setScene(Scene? arg0)
```

Parameters:

- `arg0`: `Scene?`

Returns: `Void`

#### `setTitle`

```norm
Void setTitle(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `show`

```norm
Void show()
```

Returns: `Void`

#### `toFront`

```norm
Void toFront()
```

Returns: `Void`

### `stageNew`

```norm
Stage stageNew()
```

Returns: `Stage`

## `javafx`

Source: `StringProperty.norm`

### `StringProperty`

```norm
class StringProperty extends ReadOnlyStringProperty implements Property<String>, WritableStringValue, ReadOnlyProperty<String>, ObservableStringValue
```

#### `StringProperty`

```norm
StringProperty(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx`

Source: `Styleable.norm`

### `Styleable`

```norm
interface Styleable
```

## `javafx`

Source: `Tab.norm`

### `Tab`

```norm
class Tab implements EventTarget, Styleable
```

#### `Tab`

```norm
Tab(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getContent`

```norm
Node? getContent()
```

Returns: `Node?`

#### `setClosable`

```norm
Void setClosable(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

#### `setContent`

```norm
Void setContent(Node? arg0)
```

Parameters:

- `arg0`: `Node?`

Returns: `Void`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

### `tabNew`

```norm
Tab tabNew()
```

Returns: `Tab`

## `javafx`

Source: `TabPane.norm`

### `TabPane`

```norm
class TabPane extends Control implements Skinnable, EventTarget, Styleable
```

#### `TabPane`

```norm
TabPane(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getSelectionModel`

```norm
SingleSelectionModel<Tab>? getSelectionModel()
```

Returns: `SingleSelectionModel<Tab>?`

#### `getTabs`

```norm
ObservableList<Tab>? getTabs()
```

Returns: `ObservableList<Tab>?`

### `tabPaneNew`

```norm
TabPane tabPaneNew()
```

Returns: `TabPane`

## `javafx`

Source: `TextArea.norm`

### `TextArea`

```norm
class TextArea extends TextInputControl implements Skinnable, EventTarget, Styleable
```

#### `TextArea`

```norm
TextArea(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `getText`

```norm
String? getText()
```

Returns: `String?`

#### `getText`

```norm
String? getText(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `String?`

#### `setEditable`

```norm
Void setEditable(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

#### `setMaxWidth`

```norm
Void setMaxWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setPrefRowCount`

```norm
Void setPrefRowCount(Integer arg0)
```

Parameters:

- `arg0`: `Integer`

Returns: `Void`

#### `setPromptText`

```norm
Void setPromptText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setWrapText`

```norm
Void setWrapText(Boolean arg0)
```

Parameters:

- `arg0`: `Boolean`

Returns: `Void`

#### `textProperty`

```norm
StringProperty? textProperty()
```

Returns: `StringProperty?`

### `textAreaNew`

```norm
TextArea textAreaNew()
```

Returns: `TextArea`

## `javafx`

Source: `TextField.norm`

### `TextField`

```norm
class TextField extends TextInputControl implements Skinnable, EventTarget, Styleable
```

#### `TextField`

```norm
TextField(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `clear`

```norm
Void clear()
```

Returns: `Void`

#### `getText`

```norm
String? getText()
```

Returns: `String?`

#### `getText`

```norm
String? getText(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `String?`

#### `setMaxWidth`

```norm
Void setMaxWidth(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `Void`

#### `setOnAction`

```norm
Void setOnAction(Function<Void(ActionEvent?)>? arg0)
```

Parameters:

- `arg0`: `Function<Void(ActionEvent?)>?`

Returns: `Void`

#### `setPromptText`

```norm
Void setPromptText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `textProperty`

```norm
StringProperty? textProperty()
```

Returns: `StringProperty?`

### `textFieldNew`

```norm
TextField textFieldNew()
```

Returns: `TextField`

## `javafx`

Source: `TextInputControl.norm`

### `TextInputControl`

```norm
class TextInputControl extends Control implements Skinnable, EventTarget, Styleable
```

#### `TextInputControl`

```norm
TextInputControl(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getText`

```norm
String? getText()
```

Returns: `String?`

#### `getText`

```norm
String? getText(Integer arg0, Integer arg1)
```

Parameters:

- `arg0`: `Integer`
- `arg1`: `Integer`

Returns: `String?`

#### `setPromptText`

```norm
Void setPromptText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `setText`

```norm
Void setText(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `Void`

#### `textProperty`

```norm
StringProperty? textProperty()
```

Returns: `StringProperty?`

## `javafx`

Source: `VBox.norm`

### `VBox`

```norm
class VBox extends Pane implements EventTarget, Styleable
```

#### `VBox`

```norm
VBox(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

#### `getChildren`

```norm
ObservableList<Node>? getChildren()
```

Returns: `ObservableList<Node>?`

### `vBoxNew`

```norm
VBox vBoxNew(Double arg0)
```

Parameters:

- `arg0`: `Double`

Returns: `VBox`

### `vBoxSetVgrow`

```norm
Void vBoxSetVgrow(Node? arg0, Priority? arg1)
```

Parameters:

- `arg0`: `Node?`
- `arg1`: `Priority?`

Returns: `Void`

## `javafx`

Source: `Window.norm`

### `Window`

```norm
class Window implements EventTarget
```

#### `Window`

```norm
Window(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.animation`

Source: `animation/Interpolatable.norm`

### `Interpolatable`

```norm
interface Interpolatable<T>
```

Type parameters:

- `T`

## `javafx.beans.binding`

Source: `beans/binding/BooleanExpression.norm`

### `BooleanExpression`

```norm
class BooleanExpression implements ObservableBooleanValue
```

#### `BooleanExpression`

```norm
BooleanExpression(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.beans.binding`

Source: `beans/binding/IntegerExpression.norm`

### `IntegerExpression`

```norm
class IntegerExpression extends NumberExpressionBase implements ObservableIntegerValue, NumberExpression
```

#### `IntegerExpression`

```norm
IntegerExpression(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.beans.binding`

Source: `beans/binding/NumberExpression.norm`

### `NumberExpression`

```norm
interface NumberExpression extends ObservableNumberValue
```

## `javafx.beans.binding`

Source: `beans/binding/NumberExpressionBase.norm`

### `NumberExpressionBase`

```norm
class NumberExpressionBase implements NumberExpression
```

#### `NumberExpressionBase`

```norm
NumberExpressionBase(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.beans.binding`

Source: `beans/binding/StringExpression.norm`

### `StringExpression`

```norm
class StringExpression implements ObservableStringValue
```

#### `StringExpression`

```norm
StringExpression(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.beans.property`

Source: `beans/property/Property.norm`

### `Property`

```norm
interface Property<T> extends ReadOnlyProperty<T>, WritableValue<T>
```

Type parameters:

- `T`

## `javafx.beans.property`

Source: `beans/property/ReadOnlyBooleanProperty.norm`

### `ReadOnlyBooleanProperty`

```norm
class ReadOnlyBooleanProperty extends BooleanExpression implements ReadOnlyProperty<Boolean>, ObservableBooleanValue
```

#### `ReadOnlyBooleanProperty`

```norm
ReadOnlyBooleanProperty(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.beans.property`

Source: `beans/property/ReadOnlyIntegerProperty.norm`

### `ReadOnlyIntegerProperty`

```norm
class ReadOnlyIntegerProperty extends IntegerExpression implements ReadOnlyProperty<Number>, ObservableIntegerValue, NumberExpression
```

#### `ReadOnlyIntegerProperty`

```norm
ReadOnlyIntegerProperty(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.beans.property`

Source: `beans/property/ReadOnlyProperty.norm`

### `ReadOnlyProperty`

```norm
interface ReadOnlyProperty<T> extends ObservableValue<T>
```

Type parameters:

- `T`

## `javafx.beans.property`

Source: `beans/property/ReadOnlyStringProperty.norm`

### `ReadOnlyStringProperty`

```norm
class ReadOnlyStringProperty extends StringExpression implements ReadOnlyProperty<String>, ObservableStringValue
```

#### `ReadOnlyStringProperty`

```norm
ReadOnlyStringProperty(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.beans.value`

Source: `beans/value/ObservableBooleanValue.norm`

### `ObservableBooleanValue`

```norm
interface ObservableBooleanValue extends ObservableValue<Boolean>
```

## `javafx.beans.value`

Source: `beans/value/ObservableIntegerValue.norm`

### `ObservableIntegerValue`

```norm
interface ObservableIntegerValue extends ObservableNumberValue
```

## `javafx.beans.value`

Source: `beans/value/ObservableNumberValue.norm`

### `ObservableNumberValue`

```norm
interface ObservableNumberValue extends ObservableValue<Number>
```

## `javafx.beans.value`

Source: `beans/value/ObservableObjectValue.norm`

### `ObservableObjectValue`

```norm
interface ObservableObjectValue<T> extends ObservableValue<T>
```

Type parameters:

- `T`

## `javafx.beans.value`

Source: `beans/value/ObservableStringValue.norm`

### `ObservableStringValue`

```norm
interface ObservableStringValue extends ObservableObjectValue<String>
```

## `javafx.beans.value`

Source: `beans/value/WritableBooleanValue.norm`

### `WritableBooleanValue`

```norm
interface WritableBooleanValue extends WritableValue<Boolean>
```

## `javafx.beans.value`

Source: `beans/value/WritableObjectValue.norm`

### `WritableObjectValue`

```norm
interface WritableObjectValue<T> extends WritableValue<T>
```

Type parameters:

- `T`

## `javafx.beans.value`

Source: `beans/value/WritableStringValue.norm`

### `WritableStringValue`

```norm
interface WritableStringValue extends WritableObjectValue<String>
```

## `javafx.beans.value`

Source: `beans/value/WritableValue.norm`

### `WritableValue`

```norm
interface WritableValue<T>
```

Type parameters:

- `T`

## `javafx.event`

Source: `event/ActionEvent.norm`

### `ActionEvent`

```norm
class ActionEvent extends Event implements Cloneable, Serializable
```

#### `ActionEvent`

```norm
ActionEvent(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.scene.control`

Source: `scene/control/ButtonBase.norm`

### `ButtonBase`

```norm
class ButtonBase extends Labeled implements Skinnable, EventTarget, Styleable
```

#### `ButtonBase`

```norm
ButtonBase(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.scene.control`

Source: `scene/control/ButtonType.norm`

### `ButtonType`

```norm
class ButtonType
```

#### `ButtonType`

```norm
ButtonType(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.scene.control`

Source: `scene/control/Control.norm`

### `Control`

```norm
class Control extends Region implements Skinnable, EventTarget, Styleable
```

#### `Control`

```norm
Control(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.scene.control`

Source: `scene/control/Dialog.norm`

### `Dialog`

```norm
class Dialog<R> implements EventTarget
```

Type parameters:

- `R`

#### `Dialog`

```norm
Dialog(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.scene.control`

Source: `scene/control/DialogEvent.norm`

### `DialogEvent`

```norm
class DialogEvent extends Event implements Cloneable, Serializable
```

#### `DialogEvent`

```norm
DialogEvent(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.scene.control`

Source: `scene/control/SelectionModel.norm`

### `SelectionModel`

```norm
class SelectionModel<T>
```

Type parameters:

- `T`

#### `SelectionModel`

```norm
SelectionModel(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

## `javafx.scene.control`

Source: `scene/control/Skinnable.norm`

### `Skinnable`

```norm
interface Skinnable
```

## `javafx.stage`

Source: `stage/WindowEvent.norm`

### `WindowEvent`

```norm
class WindowEvent extends Event implements Cloneable, Serializable
```

#### `WindowEvent`

```norm
WindowEvent(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`


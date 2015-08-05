# TextBoxWatermarkExtender

TextBoxWatermark is an ASP.NET AJAX extender that can be attached to an ASP.NET TextBox control to get "watermark" behavior. When a watermarked TextBox is empty, it displays a message to the user with a custom CSS style. Once the user has typed some text into the TextBox, the watermarked appearance goes away. The typical purpose of a watermark is to provide more information to the user about the TextBox itself without cluttering up the rest of the page.

*Namespace*: AjaxControlToolkit 

## Methods

**OnLoad**

OnLoad override to register a submit script for each TextBoxWatermark behavior as well as check to see if it's focused by default.

*Params*:

* **e**:

## Properties

**WatermarkCssClass**

The CSS class to apply to the TextBox when it has no value (e.g. the watermark text is shown).

**WatermarkText**

The text to show when the control has no value.

## Events

## Client methods

**clearText**

Clear the text from the target

*Params*

**focusing**

whether or not we are focusing on the textbox

*Type*: Boolean

**registerPropertyChanged**

Method called to hook up to Sys.Preview.UI.TextBox if present

**Note**: This method must be called manually if the Sys.Preview.UI.TextBox is added after the TextBoxWatermarkBehavior is initialized.

## Client properties

**watermarkText**

The text to show when the control has no value

**getter**: get_WatermarkText

**setter**: set_WatermarkText

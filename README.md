# Windows Forms Dotnet Control Collection
Check back here often this is a work in progress here you will find many extened dotnet controls for win forms in one place.

When completed my intention is to upload a list of dll files for each control so theycan be added to the toolbox.

This will take some time to complete I currently have around 12 controls and more to come.

When possible I will post a link to each controls source code.

If you have any suggestions for Free Controls with source code that you think is usefull and should be added to the list email me <a href="mailto:dwainsnickles@hotmail.com">Send Email</a>

<mark><b> [Donations Appreciated To Help Keep this project going]: [https://www.paypal.com/donate/?hosted_button_id=AG9C7PHHDWEXC) </b></mark>

To keep this project going with update and future control and would like to donate 

<a id="Top"></a>

<a rel="noopener" target="_blank" href="#CropControl"> 1) Add a crop control to any control

<a rel="noopener" target="_blank" href="#KnobControl"> 2) Knob Control

<a rel="noopener" target="_blank" href="#ProgressbarPlusControl"> 3) Progressbar Control

<a rel="noopener" target="_blank" href="#ColorSlderControl"> 4) Slider Control

<a rel="noopener" target="_blank" href="#theGrouper"> 5) Groupbox with nice features

<a rel="noopener" target="_blank" href="#ToggleSwitch"> 6) Toggle Switch

<a rel="noopener" target="_blank" href="#XPPanel"> 7) XP Panel

<a rel="noopener" target="_blank" href="#ColorComboBox"> 8) Color ComboBox

<a rel="noopener" target="_blank" href="#ColorPickerControl"> 9) Color Picker Control

<a rel="noopener" target="_blank" href="#TextEditorControl"> 10) A Full Featured Editor Based on the Richtext Box

<a rel="noopener" target="_blank" href="#CustomPanelControl"> 11) Panel wth 3d graphics plus allows individual corners to be rounded. Link includes both VB.Net and C#.

<a rel="noopener" target="_blank" href="#ExpandabePanelControl"> 12) Expandable and colapsable panel control.

<a rel="noopener" target="_blank" href="#GlassButtonControl"> 13) 3d Glass button control.

<a rel="noopener" target="_blank" href="#TrackbarControl"> 14) Advanced TrackBar (Slider) Control with MAC Style (C# & VB.NET).

<a rel="noopener" target="_blank" href="#RibbonControl"> 15) Win form Ribbon Control.

Some of these controls have been modified by me to include properties that I thought would improve the original code.
<a id="CropControl"></a>
<mark><b> [Crop Control Source Code]: https://github.com/DwainSnickles/ControlCrop </b></mark>
1) My cropper Control the idea was to be able to add a crop control from the toolbpox. I was sucessful in adding it to the form but not as a toolbox control. Problem wwas as I found out a control in the toolbox must not contain any parameters in my case I wanted to pass any control. Second problem was I could add the cotrol but it wasnt trasnparent. I,ll be working on that if anyone has any ideas drop me a note.
2) <mark><b>Screenshot</mark></b>
   
![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/033bead5-bd0c-4ff4-8140-e39563f6e9b4)

Usage is simple 

<code>Create an instance of the crop class in form

 ControlCrop ControlrectPanel;

 public frmCrop()
 {
     InitializeComponent();

     //Set crop control for each control that requires cropping

     //Set the Control in this case panel to add crop rectangle
     ControlrectPanel = new ControlCrop(pnlCrop);
     ControlrectPanel.SetControl(this.pnlCrop);

     //Set the Control in this case Picturebox to add crop rectangle
     ControlrectPicturebox = new ControlCrop(picCrop);
     ControlrectPicturebox.SetControl(this.picCrop);

 }</code>

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>
<a id="KnobControl"></a>

3) Knob Control is a Circular knob with increments fully customizable.
4) 
5) <mark><b> [Knob Control Source Code]: [https://www.c-sharpcorner.com/article/knob-control-using-windows-forms-and-gdi/ </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/5a12fe76-5db4-4fe5-9c2f-0fc3a6ef5535)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="XPPanel"></a>

5) <mark><b> [XP Panel Source Code]: [(https://www.codeproject.com/Articles/7332/Full-featured-XP-Style-Collapsible-Panel </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/89970a00-e286-49b6-8055-8f5684df890d)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="ProgressbarPlusControl"></a>

Progressbar Plus offer both horizontal and vertical operations along with text for progress and many extras. This control was written in VB.net and Converted to C# by me. I will post the vbnet link and the converted link here.

<mark><b> [(VB.Net)Progressbar Plus Source Code]: [https://www.mozilla.orghttp://www.reddit.com https://github.com/DwainSnickles/ControlCrop](https://www.codeproject.com/articles/26518/custom-progressbar-control) </b></mark>
<mark><b> [(Converted C# Version)Progressbar Plus Source Code]: [https://github.com/DwainSnickles/Progbar-Plus/tree/master </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/6e9f4aa0-b5b7-4acc-8b50-566d56a6a437)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="ColorSlderControl"></a>

Color Sluder control is a cool

<mark><b> [Slider Control Source Code]: [(https://github.com/fabricelacharme/ColorSlider </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/8d8b0084-c8d0-4846-aedc-a4ff25885485)

<a id="theGrouper"></a>

4) <mark><b> [Groupbox Source Code]: [https://www.codeproject.com/Articles/12421/The-Grouper-A-Custom-Groupbox-Control) </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/2b7e06a3-dd31-4f36-9c9c-62b54d362c8d)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="ToggleSwitch"></a>

<mark><b> [Toggle Switch Source Code]: [(https://github.com/ejensen/toggle-switch-control) </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/c51a732e-ea05-485e-8388-14bc5e003b83)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="ColorComboBox"></a>

<mark><b> [Color Combobox Source Code]: [[https://www.codeproject.com/articles/34332/color-picker-combo-box-2)) </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/bfcb9df2-9296-4f7c-abd9-2f0e5664b0bc)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="ColorPickerControl"></a>

<mark><b> [Color Picker Source Code]: [(https://www.codeproject.com/Articles/21965/Color-Picker-with-Color-Wheel-and-Eye-Dropper) </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/5127d328-0a44-4f96-9cc6-69ab54888378)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="TextEditorControl"></a>

<mark><b> [Text Editor Source Code]: [https://www.codeproject.com/Articles/1191753/A-Full-Featured-Editor-Based-on-the-Richtext-Box-3 </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/eaf25811-8960-4f65-91d8-5d4183b6a940)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="CustomPanelControl"></a>

<mark><b> [Rounded Panel Source Code]: [https://www.codeproject.com/Articles/7641/Customising-the-NET-Panel-Control </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/9b5b767f-7867-4103-b3c8-dc2ecd9bf7d8)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="ExpandabePanelControl"></a>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/06bfd9ef-7d24-44ec-83dd-d9592299f72c)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="GlassButtonControl"></a>

<mark><b> [Glass Button Source Code]: [https://www.codeproject.com/articles/18000/enhanced-glassbutton-using-gdi </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/6d655243-fa99-496d-aa3d-cbc9618f52c0)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="TrackbarControl"></a>

<mark><b> [Slider Trackbar Source Code]: [https://www.codeproject.com/Articles/14378/Advanced-TrackBar-Slider-Control-with-MAC-Style-C </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/adfcd051-97cb-461b-93b5-b0e485042546)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="RibbonControl"></a>

<p>  Windows forms Ribbon is still a little buggy. However its a reall good ribbon control. </p>

<mark><b> [Ribbon Source Code]: [(https://github.com/harborsiem/WindowsRibbon)</b></mark>

<mark><b> [Ribbon Tutorial]: [https://www.codeproject.com/articles/62412/windows-ribbon-for-winforms-part-1-introduction))</b></mark>

![image](https://github.com/user-attachments/assets/13c0629f-6550-44ba-bb8a-9f04c6733d25)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<!--

<a id="ColorPickerCotrol"></a>

<mark><b> [Text Editor Source Code]: [[[https://github.com/alexander-makarov/ExpandCollapsePanel/tree/master))) </b></mark>
<mark><b> [Color Picker Source Code]: [[link)) </b></mark>

image

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>
-->


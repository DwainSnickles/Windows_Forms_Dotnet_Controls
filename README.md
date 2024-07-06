z# Windows Forms Dotnet Control Collection
Check back here often this is a work in progress here you will find many extened dotnet controls for win forms in one place.

This will take some time to complete I currently have around 12 controls and more to come.

When possible I will post a link to each controls source code.

<--- Back to Top use ID top -->
<a id="Top"></a>

<a rel="noopener" target="_blank" href="#KnobControl">Knob Control

<a rel="noopener" target="_blank" href="#NextControl">Next Control

Some of these controls have been modified by me to include properties that I thought would improve the original code.

<mark><b> [Crop Control Source Code]: https://www.mozilla.orghttp://www.reddit.com https://github.com/DwainSnickles/ControlCrop </b></mark>
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

3) Knob Control is a Circular knob with inrements fully customizable.
4) <mark><b> [Knob Control Source Code]: [https://www.mozilla.orghttp://www.reddit.com https://github.com/DwainSnickles/ControlCrop](https://www.c-sharpcorner.com/article/knob-control-using-windows-forms-and-gdi/) </b></mark>

![image](https://github.com/DwainSnickles/Windows_Forms_Dotnet_Controls/assets/26853477/5a12fe76-5db4-4fe5-9c2f-0fc3a6ef5535)

<a rel="noopener" target="_blank" href="#Top">Back To Controls</a>

<a id="NextControlControl"></a>


 

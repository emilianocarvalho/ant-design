---
order: 9
title:
  zh-CN: 数据录入
  en-US: Data Entry
---

Data entry is an important way to get the object information, users will frequently increase, modify or delete information. A wide variety of text entry and selection input methods help users to more clearly and efficiently complete this experience. Designers should be aware of these points：

- Provide easy-to-understand copywriters for beginners / occasional users "Label"；Provide professional terminology as a domain expert "Label"。The When the user needs to provide sensitive information, through the "dark tips" to explain why the system to do so, for example: need to obtain identity card number, mobile phone number；
- So that users can get information in the context to help him complete the input. Use "good defaults", "structured formats", "dark tips", "input reminders", etc., to avoid allowing users to guess input in the blank.

---

## Text entry

The input box provides the user with the control of editing the text, which is the most basic and common way to enter the data.

### The text box (Input)

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/BPMNkGkHFqbBCRMUdfRh.png">

Enter less total number of characters, using a single line of input.

> Note: You can use special styles for some text (such as numbers and URLs). See [Input Box](/components/input/)。

### Text field（Textarea）

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/QVRSSdYrWjthpCOupqON.png">

Enter a single piece of text that uses multiple lines of text。

### Tips and help

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/KSWwgpyjPkbwclNvbvvR.png" alt="Basic style">

To improve data entry efficiency, you can usually add a dark hint in the input box to help remind the user.

> Note: The input box is usually used with the label, label (label) default on the left side of the input area, when the copy is too long or English environment can also be placed in the top, but the same system to maintain unity.

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/RtFCPKSMfRlgISbMJJRy.png" description="When the presentation is longer, you can use an "info" icon or a reminder tool.">

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/rElfIRpcmLsCTFzZDINy.png" description="
For those short input reminders (shorter than one), you can place them below the input box.">

### search for（Search）

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/ycPmRlbZtsoYAibbwMCZ.png">

Search allows users to narrow their target range in a huge pool of information and quickly get the information they need.

---

## Select entry

Allowing the user to select in a predetermined range.

#### Radio button

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/EvxgOJzHiQAxpuRaEhbH.png">

The radio button allows the user to select an option from multiple options. Radio All options are visible by default, making it easier for users to select in the comparison, so the options should not be too much.

> Note: Radio button (Radio Button) must be more than 2, generally less than 5.

### Checkbox

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/duKUrQDKiyPnYaWtvkQK.png">

Check box is used to make multiple selections in a set of options.

> Note:
> 1. Checkbox is generally used for status tags, and the need to submit with the operation;
> 2. A single check box can indicate a switch between the two states.

### Switch (Switch)

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/aIdIORGzFNjqMwrmiguZ.png">

Used to toggle the status of individual options. The inline label of the "switch" should be clear, for example: disabled / enabled, not allowed / allowed.

<br />

<img class="preview-img no-padding good" align="right" src="https://zos.alipayobjects.com/rmsportal/qoqGjsZYATDiXiWEjNIK.png" alt="Correct demonstration">
<img class="preview-img no-padding bad" align="right" src="https://zos.alipayobjects.com/rmsportal/ZcWvStIELApkpnkDOWDG.png" alt="Wrong demonstration" description="Switching the "switch" results will take effect immediately and do not need to be used with the operation buttons.">

> Note: When the user switches the "switch" button will trigger the status change directly.

### Select a list（Dropdown）

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/iGSmUHkADwVyhuTOBkpJ.png">

The selection list (commonly referred to as the drop-down menu) allows the user to select an option or multiple options from the list to provide more flexibility for the number of options on the user.

> Note:
> 1. When the option is more than 5 when used;
> 2. The list options are sorted logically and try to make the content complete.

### Slider selection（Slider）

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/JJZycUHtpopKCMxXyQpx.png">

Slider selection You can select an appropriate value by sliding the anchor point in a continuous or intermittent interval. This interactive feature makes it an excellent choice when setting options such as volume, brightness, color saturation, etc. that need to reflect the intensity level.

<br />

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/hWhUUUzikHarZSBhefDI.png">

> Note: Users can use the "continuous slider" for a more flexible and convenient operation without requiring precise values. When the user needs precise values, they can be used with the "digital input box".

### Shuttle box（Transfer）

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/VpfyicZPlNugqEjQKSDf.png">

The shuttle box moves the elements in two columns in an intuitive way to complete the selection behavior.

### Date selector（DatePicker）

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/gaaLemRmjgNpcnlthmkr.png">

The date selector provides the user with a visual way to browse and select a date or date range.

---

## File Upload（Upload）

Uploading is the process of publishing local local information (including local and cloud storage) to a remote server via web pages or uploading tools.

### Just click to upload

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/aqMzAypQRBkmWfMOpOCE.png">

Generally used for a single upload and do not need to preview the effect of the file upload, click the button to pop up the file selection box.

### Show thumbnail upload

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/oUsyeTsjadJfieTspgVq.png">

Generally used for image file upload, the user can upload pictures and display thumbnails in the list. When the number of uploads reaches the limit, the upload button disappears.

### Drag and drop

<img class="preview-img no-padding" align="right" src="https://zos.alipayobjects.com/rmsportal/euEBewdgKmhThFWrWHIm.png">

Drag the file into the specified area, complete the upload, the same support click upload.

> Note: Please upload file to provide a clear file size and file format, for example: Please select the size of not more than 5M text file (support PDF.ZIP.EXL), upload need to have a clear progress tips.

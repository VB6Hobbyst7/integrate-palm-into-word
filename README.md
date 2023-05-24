![analytics-in-motion-banner-integrate-palm-into-word](https://github.com/analyticsinmotion/integrate-palm-into-word/assets/52817125/033bcd13-2311-40a3-a2e7-0d08f0d72689)

<h1 align="center">Integrate PaLM into Word</h1>

<!-- badges: start -->
<div align="center">
  
[![MIT license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/analyticsinmotion/add-gpt-chatbot-to-microsoft-word/blob/main/LICENSE.md)&nbsp;&nbsp;
![](https://img.shields.io/badge/Maintained%3F-yes-green.svg)&nbsp;&nbsp;
[![Lifecycle:Beta](https://img.shields.io/badge/Lifecycle-Beta-ff7f2a)](https://shields.io/)&nbsp;&nbsp;
![Windows](https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white)&nbsp;&nbsp;
![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?logo=microsoft-word&logoColor=white)&nbsp;&nbsp;
  
</div>
<!-- badges: end -->

<!-- DESCRIPTION -->
## Description
Rapidly test, utilize, and compare Google's latest language model **PaLM2** in Microsoft Word. PaLM 2 is a state-of-the-art language model that boasts upgraded features in terms of its multilingual capacity, reasoning ability, and coding capabilities.
By integrating PaLM 2 into Microsoft Word, this project aims to make the latest in Google's advanced AI capabilities directly accessible and easy to use.
<br /><br />

<!-- GETTING STARTED -->
## Getting Started
### Dependencies
- Requires an MakerSuite API Key (apply for the waitlist here: <a href="https://makersuite.google.com/app/apikey">https://makersuite.google.com/app/apikey</a>)
- Requires Microsoft Windows 10/11 (<a href="https://www.microsoft.com/en-au/windows">https://www.microsoft.com/en-au/windows</a>)
- Requires Microsoft Word 365 (<a href="https://www.microsoft.com/en-us">https://www.microsoft.com/en-us</a>)

Please be aware that access to PaLM API and Makersuite are currently only available in the *United States*. To monitor available regions please check here: [https://developers.generativeai.google/available_regions](https://developers.generativeai.google/available_regions)

In addition, the PaLM API is currently in public preview. Please read the [PaLM API and MakerSuite Additional Terms of Service](https://developers.generativeai.google/terms) for more information. 
<br /><br />

<!-- Installation -->
## Installation

There are 4 basic steps in order to add PaLM's Text Generation capability into Microsoft Word:
  1. Enable the Developer Tab
  2. Import the VBA script file
  3. Create the PaLM Text Completion button
  4. Add your MakerSuite API Key

Each of these steps are fully outlined in the expandable sections below. 

<details>
  <summary><h3>&nbsp;Enable the Developer Tab</h3></summary>

The Developer tab isn't displayed by default, but you can add it to the ribbon.

**Step 1** - On the File tab, go to Options > Customize Ribbon.

**Step 2** - Under Customize the Ribbon and under Main Tabs, select the Developer check box.

  
<img src=".github/assets/images/enable-developer-tab-highlighted.png" width=80% height=80%>
<br />

The latest instructions to enable the Developer Tab from Microsoft can be found here: 
<a href="https://support.microsoft.com/en-us/office/show-the-developer-tab-in-word-e356706f-1891-4bb8-8d72-f57a51146792">https://support.microsoft.com/en-us/office/show-the-developer-tab-in-word-e356706f-1891-4bb8-8d72-f57a51146792</a>
</details>

<details>
  <summary><h3>&nbsp;Import the VBA script file</h3></summary>

**Step 1** - Download and Save the latest ```PalmText.bas``` file from the src/windows folder in this repository.
<br />

Keep the location of where the file is saved as you will need it later.<br />

**Step 2** - On the Developer tab, click the Visual Basic button.
<img src=".github/assets/images/developer-tab-visual-basic.png" width=100% height=100%>
<br />

**Step 3** - On the File tab, go to Import File...

<img src=".github/assets/images/visual-basic-file-import-section.png" width=100% height=100%>
<br />


**Step 4** - Select the ```PalmText.bas``` file and click Open
</details>



### Create the PaLM Text Completion button

*Please Note:* This project uses the same ribbon as three of our other projects: 
 - **Add ChatGPT to Microsoft Word** - project can be found <a href="https://github.com/analyticsinmotion/add-chatgpt-to-microsoft-word">here</a> 
 - **Create Images with DALL·E in Microsoft Word** - project can be found <a href="https://github.com/analyticsinmotion/create-images-with-dall-e-in-microsoft-word">here</a> 
 - **Add GPT Chatbot to Microsoft Word** - project can be found <a href="https://github.com/analyticsinmotion/add-gpt-chatbot-to-microsoft-word">here</a>

If you have have already added any one of these projects into Microsoft Word you can start at Step 3 of this section.
<br /><br />

**Step 1** - Add a new tab
<br />
  - On the File tab, go to Options > Customize Ribbon
  - Click New Tab
<br />

<img src=".github/assets/images/options-customize-ribbon-new-tab.png" width=40% height=40%>
<br />

 **Step 2** - Rename the New Tab to **AI Assistant**

<img src=".github/assets/images/options-customize-ribbon-rename-tab.png" width=35% height=35%>
<br />

**Step 3** - Rename New Group (Custom) to **PaLM**

<img src=".github/assets/images/rename-new-group.png" width=35% height=35%>
<br />

**Step 4** - Select Macros in the Choose Commands from dropdown box

<img src=".github/assets/images/choose-commands-from-macros.png" width=35% height=35%>
<br />

**Step 5** - Select the PaLMText Macro and click Add >>

<img src=".github/assets/images/add-the-macro-into-new-group.png" width=75% height=75%>
<br />

**Step 6** - Rename button from *Normal.PalmText.PalmText* to **Text Completion**, select a Symbol and click OK

<img src=".github/assets/images/rename-button.png" width=35% height=35%>
<br />


After the preceding steps have been completed the Microsoft Word screen should look like the following:

<img src=".github/assets/images/screen-after-chatbot-buttons-added.png" width=100% height=100%>
<br />



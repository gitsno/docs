---
title: "Widgets"
category: "Page Editor"
description: "Describes widgets in Mendix Studio."
tags: ["studio", "page editor", "pages", "widgets"]
---

## 1 Introduction

Widgets are single user-interface elements that can be configured: for example, a drop-down menu or different kinds of buttons.

{{% image_container width="300" %}}![](attachments/page-editor-widgets/widgets-examples.png)
{{% /image_container %}}

Widgets in Studio are grouped by category and can be classified by their origin.

## 2 Viewing Widgets

To view widgets in Mendix Studio, do the following:

1. Click the **Pages** icon in the left menu bar.

2. In the displayed list of app pages, select the page you want to open and click it.

3. In the **Toolbox** tab, click **Widgets**.

   ![](attachments/page-editor-widgets/toolbox-widgets.png)

## 3 Widgets by Category {#widget-categories}

Widgets of Studio are divided into categories that you can see when you open the **Widgets** tab.

{{% image_container width="350" %}}![](attachments/page-editor-widgets/widgets-categories.png)
{{% /image_container %}}

Widget categories are described in the table below:

| Widget Category                                      | Description                                                  | Link to More Detailed Documentation                          |
| ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Data Containers                                      | Contains a data view (the starting point for showing the contents of one object),  list view (the starting point for showing the contents of list of objects), and a data grid (shows a list of objects in a table format). | [Data View & List View Properties](page-editor-data-view-list-view)<br />[Data Grid Properties](page-editor-data-grid) |
| [Input Elements](page-editor-widgets-input-elements) | Contains elements that can be used for inputting data.       | [Input Element Widgets](page-editor-widgets-input-elements)  |
| [Images](page-editor-widgets-images)                 | Contains image display widgets.                              | [Image Widgets](page-editor-widgets-images)                  |
| [Text](page-editor-widgets-text)                     | Contains text display widgets.                               | [Text Widgets](page-editor-widgets-text)                     |
| [Buttons](page-editor-widgets-buttons)               | Contains a variety of buttons for placing on a page.         | [Button Widgets](page-editor-widgets-buttons)                |
| [Layouts](page-editor-widgets-layouts)               | Contains layouts for controlling the placing widgets.        | [Layout Widgets](page-editor-widgets-layouts)                |
| [Menus](/refguide/menu-widgets)                      | Contains menu creation widgets. Currently, these widgets can be configured only in Studio Pro. | [Menu Widgets](/refguide/menu-widgets) in the *Mendix Studio Pro Guide* |
| Display                                              | Contains widgets which display changing elements on a page, for example a map, or a progress bar. This category consists of the App Store widgets. | section [4 Widgets by Origin](#widgets-by-origin)            |
| Charts                                               | Contains different charts. This category consist of the App Store widgets. | section [4 Widgets by Origin](#widgets-by-origin)            |
| List view Controls                                   | Contains controls for the list view. This category consist of the App Store widgets. | section [4 Widgets by Origin](#widgets-by-origin)            |
| Add-ons                                              | Contains all custom widgets previously installed in the app. If widgets cannot be matched to the App Store profile they will be shown in the add-ones. |                                                              |

## 4 Widgets by Origin {#widgets-by-origin}

Widgets in Studio can be divided by origin as shown in the table below:

| Type              | Description                                                  | Origin                                                       |
| ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Default widgets   | Widgets that are included into your app by default and do not have the information icon in the top-right corner. | Apps created in the Developer Portal. For more information on the Developer Portal, see [Developer Portal](https://docs.mendix.com/developerportal/). |
| App Store widgets | Widgets that are you can download to your project directly from Studio. Some App Store widgets are already in your project as a part of the app. Such widgets have the information icon in the top-right corner of widgets in the **Toolbox**. <br />For more information on the App Store, see [App Store Overview](/developerportal/app-store/app-store-overview). | [App Store](/developerportal/app-store/)                     |
| Local widgets     | Either widgets that are a part of a starter app, or widgets created by your or your team locally via Studio Pro. For more information on developing widgets, see the [Custom Widget Development](../../howto/widget-development/) how-to's. As a rule local widgets will be listed in the **Add-ons** category. For more information on categories, see section [3 Widgets by Category](#widget-categories). | Apps created in the  Developer Portal/Studio Pro        |

## 5 Adding the App Store Widgets

You can add App Store widgets to your app by downloading them directly in the **Widgets** tab in Studio. These widgets are a subset of all widgets available in the app store: you can only download the ones that are approved for use in Studio. You can also update them if an update is available.

To add an App Store widget, do the following:

1. Open the **Widgets** tab.

2.  Do one of the following: <br />

    a. Find a category with the **View App Store widgets** option and click it.  <br />

    {{% image_container width="300" %}}![](attachments/page-editor-widgets/view-app-store-widgets.png)
    {{% /image_container %}}<br />

    b.  Start typing the name of the category or of a specific widget in the **Search** field. <br />

    ![](attachments/page-editor-widgets/slider.png)

3.  Click the cloud icon to download the widget and add it to your project.

    ![](attachments/page-editor-widgets/app-store-download.png)

The widget is now added to your project, you can simply drag and drop it to the page to use it. You can also view settings of this widget in the **App Settings**.  For more information on managing widgets in your app, see [Settings](settings).

{{% alert type="info" %}}

Some similar widgets are packaged together: downloading one of these widgets will cause a number of other widgets to be downloaded as well. For example, downloading a line chart will give you all chart widgets.

{{% /alert %}}

## 6 Read More 

* [Page Editor](page-editor)
* [Settings](settings)
* [App Store Overview](/developerportal/app-store/app-store-overview)

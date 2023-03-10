---
title: "Image Uploader"
parent: "image-and-file-widgets"
tags: ["studio pro", "image uploader", "file widget", "widget"] 
#If moving or renaming this doc file, implement a temporary redirect and let the respective team know they should update the URL in the product. See Mapping to Products for more details.
---

{{% alert type="warning" %}}The image uploader widget is not supported on native mobile pages.{{% /alert %}}

## 1 Introduction

An image uploader is used to upload images to the server. It also generates a thumbnail of the uploaded image. The uploaded image or its thumbnail can be displayed by a dynamic image. It must be placed inside a data view connected to the entity System.Image or a specialization thereof.

In the example below, an image uploader is placed in a nested data view (the *Profile* entity is a specialization of System.Image):

![Image Uploader](attachments/image-and-file-widgets/image-uploader.png)

## 2 Properties

An example of image uploader properties is represented in the image below:

{{% image_container width="250" %}}![Image Uploader Properties](attachments/image-and-file-widgets/image-uploader-properties.png)
{{% /image_container %}}

Image uploader properties consist of the following sections:

* [Common](#common) 
* [Design Properties](#design-properties)
* [Editability](#editability)
* [General](#general)
* [Label](#label)
* [Visibility](#visibility)

### 2.1 Common Section {#common}

{{% snippet file="refguide/common-section-link.md" %}}

### 2.2 Design Properties Section {#design-properties}

{{% snippet file="refguide/design-section-link.md" %}} 

### 2.3 Editability Section {#editability}

{{% snippet file="refguide/editability-section-link.md" %}}

### 2.4 General Section {#general}

#### 2.4.1 Maximum file size (MB)

**Max file size (MB)** determines the maximum size of files (in megabytes) that can be uploaded.

Default: *5*

#### 2.4.2 Allowed Extensions {#allowed-extensions}

You can specify file extensions that users are allowed to upload. If no extension is specified, all file extensions are allowed. Separate multiple extensions by a semi-colon (for example, `txt;doc`).

If a file with an extension that is not allowed is selected, a [system text](system-texts) for **File manager/dynamic image** > **Error: incorrect file extension** will be shown below the file manager.

#### 2.4.3 Thumbnail Width

**Thumbnail width** determines the width of the generated thumbnail in pixels. However, the aspect ratio of the image will remain the same during thumbnail generation.

#### 2.4.4 Thumbnail Height

**Thumbnail height** determines the height of the generated thumbnail in pixels. However, the aspect ratio of the image will remain the same during thumbnail generation.

### 2.5 Label Section {#label}

{{% snippet file="refguide/label-section-link.md" %}}

### 2.6 Visibility Section {#visibility}

{{% snippet file="refguide/visibility-section-link.md" %}}

## 3 Read More

* [Page](page)
* [Images, Videos & Files](image-and-file-widgets)
* [Properties Common in the Page Editor](common-widget-properties)

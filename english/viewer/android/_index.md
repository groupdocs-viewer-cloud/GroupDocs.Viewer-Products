---
############################# Static ############################
layout: "product"
date: 2021-04-27T09:31:06+03:00
draft: false

product: "Viewer"
product_tag: "viewer"
platform: "Android"
platform_tag: "android"

############################# Head ############################
head_title: "Android Document Viewing Cloud SDK | Render PDF Word Excel Visio HTML"
head_description: "Android Cloud SDK & REST APIs to build apps for rendering & viewing images, HTML, PDF, Word, Excel, Email, Visio, Project & CAD file formats."

############################# Header ############################
title: "Render & View Documents via Android SDK"
description: "RESTful API to efficiently build Android applications for rendering & viewing documents of all popular formats. Render as HTML, PNG, JPG or PDF."
button:
    enable: true

############################# SubMenu ############################
submenu:
    enable: true
    
    left:
        img_alt: "GroupDocs.Viewer Cloud SDK for Android"
        image: "/sdk/272x272/groupdocs_viewer-for-android.webp"
        product: "GroupDocs.Viewer"
        platform: "Android"

    middle:
        button:
            # button loop
            - link: "#overview"
              text: "Overview"

            # button loop
            - link: "#features"
              text: "Features"

            

            # button loop
            - link: "https://docs.groupdocs.cloud/viewer/release-notes/"
              text: "Release Notes"

            # button loop
            - link: "https://purchase.groupdocs.cloud/pricing"
              text: "Pricing"

    right:
        link_download: "https://github.com/groupdocs-viewer-cloud/groupdocs-viewer-cloud-android"
        link_learn: "https://docs.groupdocs.cloud/viewer/"
        link_buy: "https://purchase.groupdocs.cloud/buy"

############################# Overview ############################
overview:
    enable: true
    content: |
      GroupDocs.Viewer Cloud is a true REST API that gives the complete freedom of platform & programming language whereas GroupDocs.Viewer Cloud SDK for Android is built as a layer on the top of GroupDocs.Viewer Cloud REST API, allowing a higher level of abstraction so that you don't need to know the REST API to use this SDK.

      GroupDocs.Viewer Cloud API allows you to seamlessly enhance your application with the capability to render a number of document formats with the ability to view a specific document in HTML, image, PDF or its original format. You also get the flexibility to render the whole document, page by page or custom range of pages. GroupDocs.Viewer Cloud SDK for Android has been developed to help you integrate all these features in your Android application without any hassle.

      


    tabs:
      enable: true     
      
      ## TAB ONE ##
      tab_one:
        description: |
          An overview GroupDocs.Viewer Cloud API.

        left:
          enable: true
          icon: "fa fa-cogs"
          title: "Supported Categories"
          content: |
            * Word, Excel, PowerPoint
            * Visio, Project, Outlook
            * OpenDocument
            * Images
            * CAD Drawing Image formats
            * PDF, XPS, Text, Web formats
            * OneNote & others
        right:
          enable: true
          icon: "fab fa-html5"
          title: "Feature Overview"
          content: |
            * Get Document Information
            * HTML Viewer
            * Image Viewer
            * PDF Viewer
            * Rotating & Reordering
            * Watermark Pages
            * Rendering Attachments
            
      
      ## TAB TWO ##
      tab_two:
        description: |
          GroupDocs.Viewer Cloud supports a number of document formats.

        left:
          enable: true
          table:
            # table loop
            - title: "Microsoft Office"
              content: |
                * **Word:** DOC, DOCX, DOCM, DOT, DOTX, DOTM
                * **Excel:** XLS, XLSX, XLSM, XLSB, XLTX, XLTM
                * **PowerPoint:**  PPT, PPTX, PPS, PPSX, PPSM, PPTM, POTX, POTM
                * **Visio:** VSD, VSDX, VSDM, VST, VSTX, VSTM, VSS, VSSX, VSSM, VDX, VSX, VTX, VDW
                * **Project:** MPP, MPT
                * **Outlook:** MSG, EML, PST, OST
                * **OneNote:** ONE

            

        right:
          enable: true
          table:
            # table loop
            - title: "Images, Graphics & Diagrams"
              content: |
                * **OpenDocument:** ODT, OTT, ODS, OTS, ODP, OTP, ODG
                * **Fixed Layout:** PDF, XPS
                * **eBook:** EPUB, MOBI
                * **Image Files:** BMP, GIF, ICO, JPG, JPEG, PNG, PSD, SVG, TIF, TIFF, Webp, DjVu, DNG, DCM (DICOM)
                * **JPEG2000:** JP2, J2C, J2K, JPF, JPX, JPM
                * **CAD:** DGN, DWF, DWG, DXF, IFC, STL
                * **Markup:** HTML, MHT, MHTML, XML
                * **Metafile:** WMF, EMF, CGM
                * **Apple Mail:** EMLX
                * **PostScript:** PS, EPS
                * **Other:** RTF, TXT, TEX, CSV, TSV, PCL
                
      ## TAB THREE ##
      tab_three:
        description: |
          Easily get started with GroupDocs.Viewer REST API while using your favorite language & platform.




        
        left:
          enable: true
          table:
            # table loop
            - icon: "fab fa-windows"
              title: "Operating Systems"
              content: |
                * Microsoft Windows Desktop
                * Microsoft Windows Server
                * Linux
                * MacOS

            # table loop
            - icon: "fas fa-code"
              title: "Supported Frameworks"
              content: |
                * Java 7 (1.7) and above

        right:
          enable: true
          table:
            # table loop
            - icon: "fas fa-cogs"
              title: "Development Environments"
              content: |
                * NetBeans
                * IntelliJ IDEA
                * Eclipse
            # table loop
            - icon: "fas fa-tools"
              title: "Build Automation Tool"
              content: |
                * Maven

############################# Features ############################
features:
    enable: true
    title: "Advanced Document Viewer REST API Features"

    feature:
      # feature loop
      - icon: "fab fa-html5"
        content: "Render documents as HTML5"

      # feature loop
      - icon: "fas fa-images"
        content: "Render documents as Image"

      # feature loop
      - icon: "fas fa-file-alt"
        content: "Rotate, reorder & watermark pages"
      
      # feature loop
      - icon: "fas fa-file-pdf"
        content: "Render documents as PDF"

      # feature loop
      - icon: "fas fa-paperclip"
        content: "Render document attachments"

      # feature loop
      - icon: "fas fa-lock"
        content: "APIs are secured and require authentication"

     

      

    more_feature:
      # more_feature_loop
      - title: "An Easy SDK for Developers Who Want to Save Time"
        content: |
          Using the GroupDocs Cloud APIs is quite simple as there is nothing to install. Simply create an account at GroupDocs Cloud and get your application information. Once you have the App SID & key, you are ready to give the GroupDocs Cloud REST APIs a try. The SDKs have been developed to facilitate the developers and to let them get started with our APIs real fast by hiding the REST API calls and allowing you to use the features of the API in a native way using Android as the language.
        # more_feature_loop
      - title: "Render a Number of Document Formats"
        content: |
          The cloud-based viewer API has the ability to display different document formats quickly, with just a few lines of code. Using the SDK for Android you can find out about the various document formats supported by the SDK. 
      # more_feature_loop
      - title: "Get a list of supported file formats - Android"
        content: |
          
          
          ```rb
            import com.groupdocs.cloud.viewer.client.*;
            import com.groupdocs.cloud.viewer.model.*;
            import com.groupdocs.cloud.viewer.api.InfoApi;

            public class ApiExample {
                
            public static void getSupportedFormats() {

            //TODO: Get your AppSID and AppKey at https://dashboard.groupdocs.cloud (free registration is required).
            String appSid = "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX";
            String appKey = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX";

            Configuration configuration = new Configuration(appSid, appKey);

            InfoApi infoApi = new InfoApi(configuration);

            try {
                FormatsResult response = infoApi.getSupportedFileFormats();
                for (Format format : response.getFormats()) {
                    System.out.println(format.getFileFormat());
                }
                
                } catch (ApiException e) {
                    System.err.println("Failed to get supported file formats");
                    e.printStackTrace();
                    
                }

              }
          }
          ```
      # more_feature_loop
      - title: "Efficiently Minify Output Content"
        content: "One of the most exciting features of our Cloud-based viewer API is its ability to minify the output content. Minification removes comments, extra white-spaces, and other unneeded characters without breaking the content structure. As a result, the page becomes smaller in size and loads faster. "
      
      # more_feature_loop
      - title: "Flexible Rendering of Documents"
        content: "GroupDocs.Viewer is a powerful document viewer REST API that allows you to display over 85 document formats in your applications. It allows document rendering for the whole document, page by page or custom range of pages."

      # more_feature_loop
      - title: "Customize to Suit your Needs"
        content: "GroupDocs.Viewer Cloud SDK for Android is 100% tested and out of the box running. The SDK is open source and has an MIT license. The API is easy to customize and changes can be made according to the features you need to add in your application."

      

      
       
       

############################# Support ############################
support:
    enable: true

############################# Solutions ############################
solutions:
    enable: true
    title: "GroupDocs.Viewer Cloud also offers individual document rendering SDKs for other popular languages as listed below:"

    solution:
        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for cURL"
          image: "/sdk/272x272/groupdocs_viewer-for-curl.webp"
          product: "GroupDocs.Viewer"
          platform: "cURL"
          link: "/viewer/curl/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for .NET"
          image: "/sdk/272x272/groupdocs_viewer-for-net.webp"
          product: "GroupDocs.Viewer"
          platform: ".NET"
          link: "/viewer/net/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for Java"
          image: "/sdk/272x272/groupdocs_viewer-for-java.webp"
          product: "GroupDocs.Viewer"
          platform: "Java"
          link: "/viewer/java/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for PHP"
          image: "/sdk/272x272/groupdocs_viewer-for-php.webp"
          product: "GroupDocs.Viewer"
          platform: "PHP"
          link: "/viewer/php/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for Python"
          image: "/sdk/272x272/groupdocs_viewer-for-python.webp"
          product: "GroupDocs.Viewer"
          platform: "Python"
          link: "/viewer/python/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for Android"
          image: "/sdk/272x272/groupdocs_viewer-for-android.webp"
          product: "GroupDocs.Viewer"
          platform: "Android"
          link: "/viewer/android/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for Node.js"
          image: "/sdk/272x272/groupdocs_viewer-for-node.webp"
          product: "GroupDocs.Viewer"
          platform: "Node.js"
          link: "/viewer/nodejs/"

        # solution loop
        - img_alt: "GroupDocs.Viewer Cloud SDK for Android"
          image: "/sdk/272x272/groupdocs_viewer-for-android.webp"
          product: "GroupDocs.Viewer"
          platform: "Android"
          link: "/viewer/android/"
    

############################# Back to top ###############################
back_to_top:
  enable: true
--- 
<script setup>
import { TabComponent as EjsTab, TabItemsDirective as ETabitems, TabItemDirective as ETabItem}
from "@syncfusion/ej2-vue-navigations";

const headerText0= {text: "ASP.NET"};
const headerText1= {text: "ASP.NET MVC"};
const content0= "ASP.NET is an open-source server-side web application framework designed for web development to produce " +
  "dynamic web pages. It was developed by Microsoft to allow programmers to build dynamic web sites, web applications ";
const content1= "The ASP.NET MVC is a web application framework developed by Microsoft, which implements the " +
  "model-view-controller (MVC) pattern. It is open-source software, apart from the ASP.NET Web Forms component which is ";
</script>
<template>
  <ejs-tab cssClass="tab-content e-fill" width="850" overflowMode="Popup">
    <e-tabitems>
      <e-tab-item :header="headerText0" :content="content0"></e-tab-item>
      <e-tab-item :header="headerText1" :content="content1"></e-tab-item>
    </e-tabitems>
  </ejs-tab>
  
<!-- Render Tab using HTML Elements -->

<!-- <ejs-tab cssClass="tab-content e-fill" width="850" overflowMode="Popup">
  <div class="e-tab-header">
     <div>HTML</div>
    <div>Java</div>
   <div>JavaScript</div>
    <div>VB.Net</div>
    <div>Xamarin</div>  
     <div>ASP.NET</div>
    <div>ASP.NET MVC</div> 
     <div>PHP</div>
    <div>Ruby</div>
    <div>C Sharp(C#)</div>
    <div>Python</div>
    <div>Perl</div>
    <div>SQL</div> 
  </div>
  <div class="e-content">
    <div>HyperText Markup Language is the standard markup language used to create web pages.</div>
    <div>Java is used in a wide variety of computing platforms from embedded devices and mobile phones to enterprise servers and supercomputers.</div>
    <div>JavaScript (JS) is an interpreted computer programming language. It was originally implemented as part of web browsers so that client-side scripts could interact with the user, control the browser, communicate asynchronously, and alter the document content that was displayed.</div>
    <div>The command-line compiler, VBC.EXE, is installed as part of the freeware .NET Framework SDK. Mono also includes a command-line VB.NET compiler.</div>
    <div>Xamarin is a San Francisco, California based software company created in May 2011[3] by the engineers that created Mono,[4] Mono for Android and MonoTouch that are cross-platform implementations of the Common Language Infrastructure (CLI) and Common Language Specifications (often called Microsoft .NET). With a C#-shared codebase, developers can use Xamarin tools to write native Android, iOS, and Windows apps with native user interfaces and share code across multiple platforms.[5] Xamarin has over 1 million developers in more than 120 countries around the World as of May 2015.</div> 
    <div>ASP.NET is an open-source server-side web application framework designed for web development to produce dynamic web pages. It was developed by Microsoft to allow programmers to build dynamic web sites, web applications and web services.</div>
    <div>The ASP.NET MVC is a web application framework developed by Microsoft, which implements the model-view-controller (MVC) pattern. It is open-source software, apart from the ASP.NET Web Forms component which is proprietary.</div>            
    <div>PHP is a server scripting language, and a powerful tool for making dynamic and interactive Web pages.</div>
    <div>Ruby is an interpreted, high-level, general-purpose programming language.It runs on a variety of platforms, such as Windows, Mac OS and UNIX.</div>
    <div>C# is intended to be a simple, modern, general-purpose, object-oriented programming language. Its development team is led by Anders Hejlsberg. The most recent version is C# 5.0, which was released on August 15, 2012.</div>
    <div>Python was designed with an emphasis on code readability, and its syntax allows programmers to express their concepts in fewer lines of code.</div>
    <div>Perl is a general purpose, high level interpreted and dynamic programming language. Perl supports both the procedural and Object-Oriented programming.</div>         
    <div>SQL gives you the ability to find necessary information fast and in a reliable way.</div>    
  </div>
</ejs-tab> -->
</template>

<style>
@import "../node_modules/@syncfusion/ej2-base/styles/material.css";
@import "../node_modules/@syncfusion/ej2-buttons/styles/material.css";
@import "../node_modules/@syncfusion/ej2-popups/styles/material.css";
@import "../node_modules/@syncfusion/ej2-vue-navigations/styles/material.css";

.tab-content .e-content .e-item {
    font-size: 12px;
    padding: 10px;
    text-align: justify;
}
</style>

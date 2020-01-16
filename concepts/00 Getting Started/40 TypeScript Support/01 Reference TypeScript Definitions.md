You can find the file with TypeScript definitions for DevExtreme in the DevExtreme zip archive or in the folder where you have installed DevExtreme, which is **C:\Program Files (x86)\DevExpress 16.2\DevExtreme\Sources\ts** by default. Add this file to your project. Then, reference this and jQuery TypeScript definition file in your *.ts*-file.

    /// <reference path="TypeScript/jquery.d.ts" />
    //  File from the zip archive or from the installation folder...
    /// <reference path="TypeScript/dx.all.d.ts" />
    //  ...or file from GitHub
    /// <reference path="TypeScript/devextreme.d.ts" />

You can also reference TypeScript definitions for Knockout or AngularJS.

    /// <reference path="TypeScript/knockout.d.ts" />
    /// <reference path="TypeScript/angular.d.ts" />

Along with TypeScript definitions, you need to reference the libraries themselves. See [Installation](/concepts/00%20Getting%20Started/01%20Installation '/Documentation/Guide/Getting_Started/Installation/') for detailed information.

<a href="http://www.youtube.com/watch?v=-k05YGTLp4I&list=PL8h4jt35t1wjGvgflbHEH_e3b23AA30-z&index=46" class="button orange small fix-width-155" target="_blank">Watch Video</a>

#####See Also#####
- [Configure a Widget Using TypeScript](/concepts/00%20Getting%20Started/40%20TypeScript%20Support/05%20Configure%20a%20Widget.md '/Documentation/Guide/Getting_Started/TypeScript_Support/Configure_a_Widget')

[tags]typescript support, typescript definitions
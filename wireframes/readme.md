# Wireframes
This folder contains an example which illustrates the creation of a set of wireframes from a user story. 

We use the following free tools to create and export wireframes as HTML. We can then use GitHub Pages to make them available to clients. 

Tools: 

* [Evolus Pencil](http://pencil.evolus.vn/)
* [Evolus Pencil Pretotype Plugin](https://rudylattae.github.io/evoluspencil-pretotype-template/)


Using Evolus Pencil, you can quickly create wireframes with behaviour to illustrate each feature or user story. 

Using the Pretotype plugin, you can export the wireframes and behaviour to html. 

## Ways To Install Evolus Pencil

Evolus Pencil is a prototyping and wireframing tool, which is ridiculously easy to use, and which exports your wireframes to html - so you can show them off, on GitHub Pages. It's simpler to master than AxureRP, and gives you results in half the time. 

You can use the installers on the Evolus site to install on your own machine. You can't install Evolus Pencil directly on the Univeristy machines, as they don't allow external installers to run without admin permissions. 

Some machines (those in the John Dalton Building) have `npm` available. This is the Node.JS package manager. You can use this to install Pencil from its GitHub repository.

### Building Evolus Pencil from source

1. Using GitHub desktop, clone the [Pencil repo](https://github.com/evolus/pencil) to your H:\ drive.
2. In a cmd.exe (Command Prompt) window, go to the directory you cloned to.
3. Type the command `npm install`. This will cause the Node Package Manager to download all the project dependencies listed in its `package.json` file.
4. This should complete without errors (some warnings are OK)
5. Type the command `npm start`.
6. Evolus Pencil should start, just as if you had installed it.

### Exporting as a webpage
Once you've installed Pencil, don't forget to add the [Evolus Pencil Pretotype Plugin](https://rudylattae.github.io/evoluspencil-pretotype-template/). 
It will allow you to export really fine html, which you can publish onto GitHub pages. 

#### Full instructions for use:

**Your mockup must have one page called "Start"! If you do not do this, the template will not know which of your pages to show first.**  

1. Install the template through the Pencil > Tools > Manage Export Template menu
2. Export your mockup with the template by using the Document > Export Document... wizard.
3. Choose to export a Single web page for the Output format
4. Select All pages in the document for pages to export
5. Select the Pretotype Template as your export template, provide a destination and click 'Done'.









## Broad DCC Support

The new Kartaverse RiveLink mograph toolset is being created with the goal of initially support Assimilate [Scratch](Assimilate Scratch/)/[LiveFX](https://www.assimilateinc.com/products/livefx/), BMD[Resolve](https://www.blackmagicdesign.com/products/davinciresolve)/[Fusion Studio](https://www.blackmagicdesign.com/products/fusion), and SideFX [Houdini Copernicus](https://www.sidefx.com/products/whats-new-in-h205/)  graphics software on Kartaverse 6's official launch day.

### Assimilate LiveFX

![Assimilate LiveFX](Images/Icon-Assimilate.png)

> `RiveLink for LiveFX` will be implemented as a native Assimilate Scratch [SPA plugin](https://www.assimilatesupport.com/akb/KnowledgebaseArticle50984.aspx). This allows RiveLink visuals to be rendered in realtime and displayed on an XR Stage LED video wall with multi-plane effects using LiveFX. 

(Special thanks goes out to Mazze Aderhold and Jeff at Assimilate for their support of the Kartaverse project. It is greatly appreciated!)

### BMD Resolve/Fusion

![Resolve/Fusion Icon](Images/Icon-Resolve-Fusion.png)

> `RiveLink for Resolve/Fusion` is a fuse that connects directly to the official [Rive-CPP](https://github.com/rive-app/rive-cpp) library, using the fuse API and its [LuaJIT FFI](https://luajit.org/ext_ffi.html) interface.

### SideFX Houdini Indie

![SideFX Houdini Icon](Images/Icon-Houdini.png)

> `RiveLink for Houdini Indie` will be implemented as a Houdini 20.5+ Copernicus node. Houdini's TOPs (Task Operator) automation environment can be used to batch render RiveLink motion graphics quickly with the help of the HQueue Render Manager.

# BMD Resolve/Fusion Installation

## Reactor Package Manager

> To start using Kartaverse RiveLink for BMD Resolve/Fusion you [need to follow this guide](https://kartaverse.github.io/Reactor-Docs/#/reactor) to get the Reactor package manager setup on your system. 

For most users, it only takes a few minutes to get Reactor installed.

![Install Reactor](Images/reactor-installer.png)

### What's a Package Manager?

Reactor is the package manager for BMD Resolve/Fusion. Reactor is maintained by a team of volunteers in the Fusion community. The package manager holds the macros, scripts, fuses, plugins, and example comps needed to take your compositing skills to the next level.

> Reactor content is sourced from the official [Reactor GitLab repository](https://gitlab.com/WeSuckLess/Reactor). This means you have to allow an outgoing firewall rule to the GitLab repository when you want to download new atom package updates. 

After you have Reactor installed, you might be interested to [browse a web based version](https://kartaverse.github.io/Reactor-Docs/) of the Reactor Package Manager content. This allows you to easily search through all the Reactor atom packages to find what you are looking for when you are on the go.

### KartaLink | RiveLink Atom Package

> Installation is as easy as selecting the "Kartaverse/KartaLink" category on the left sidebar. Then click on the ✅ checkbox to the left of the "KartaLink | RiveLink" atom package name to install it.

![RiveLink in Reactor](Images/rivelink-reactor.png)

### Vonk Ultra Reactor Atom Package

> Vonk Ultra lets you take your motion graphics workflows to the next level!

Vonk makes it easy to use JSON/CSV files when you need to create data driven graphics.  These external data sources can pass bi-directional event messages to the Rive state machine in your comp. 

This data driven approach allows multiple node branches of RiveLink nodes in a comp to be kept perfectly sync so your .riv based animations playback with precise timing.

> When using RiveLink, it's helpful to also install the "Vonk Ultra" data node toolset from Reactor, too. Select the "Kartaverse/Vonk Ultra" category on the left sidebar. Then click on the ✅ checkbox to the left of the "Vonk Ultra" atom package name to install it.

![Vonk Ultra in Reactor](Images/vonk-reactor.png)

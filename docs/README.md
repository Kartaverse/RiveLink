# RiveLink

> The ultimate XR motion graphics solution for Fusioneers
> Enjoy!
>

Welcome to the development repo for "RiveLink" — a [Rive.app](https://rive.app/) integration plugin for BMD Resolve/Fusion. 

With RiveLink you can effortlessly port your existing Rive.app created motion graphics so they can work inside your favorite node based compositing toolset.

- The integration plugin was made in West Dover, Nova Scotia, Canada 🇨🇦

## Usage

> Using this toolset is as easy as adding a "kvrRiveLink" node to your comp using the "Select Tool" dialog.

![Select Tool](Images/rivelink-select-tool.png)

> Select the "kvrRiveLink" node and then use the Inspector panel's "browse" button to locate your .riv file.

![Inspector Panel](Images/rivelink-inspector.png)

> Click the "Render" button near the timeline playbar area, and Fusion will output your Rive.app based animation to disk.

![RiveLink Nodes](Images/rivelink-screenshot.png)

For a simple motion graphics title, where you want to control the starting frame of the animation, you are ready to go with only three nodes in your Fusion comp:

		vNumberCompReqTime -> kvrRiveLink -> Saver/MediaOut

## Reactor Based Installation

The completed version of RiveLink will be delivered using the [Reactor Package Manager](https://kartaverse.github.io/Reactor-Docs/#/reactor) for Resolve/Fusion.

Installation is as easy as selecting the "Kartaverse/KartaLink" category on the left sidebar. Then click on the install checkbox next to the name of the "RiveLink" atom package.

![Reactor](Images/reactor.png)


When using RiveLink, it's helpful to also install the "Vonk Ultra" toolset from Reactor.This gives you have access to temporal effect based data nodes like the "vNumberCompReqTime" node that allows you to offset the initial render start frame in the timeline by modifying the comp's "requested frame" value.

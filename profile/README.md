## This is PillowMC.
We are making playing both NeoForge and Quilt mods (include Fabric mods, the same below) possible.
### Our technology roadmap
#### Pillow Loader
[NeoForged](https://github.com/neoforged)'s [FML](https://github.com/neoforged/FancyModLoader) is based on [ModLauncher](https://github.com/McModLauncher/ModLauncher), which is used for transforming Minecraft classes.

[Quilt Loader](https://github.com/QuiltMC/quilt-loader)'s upstream [Fabric Loader](https://github.com/FabricMC/fabric-loader) defines [an API called "launcher"](https://fabricmc.net/wiki/documentation:fabric_loader#launchers) for transforming classes.
This means if we make a launcher for ModLauncher, we can use Quilt Loader on ModLauncher with FML, and we can use Quilt (and Fabric) mods. This is what [Pillow Loader](https://github.com/PillowMC/pillow) do.

#### ShearAPI
NeoForge itself contains patches, which make Quilt mods' mixins can't work well. So we create [ShearAPI](https://github.com/PillowMC/ShearAPI).

## Contribution guidelines
You must sign off for [DCO](https://developercertificate.org/).
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

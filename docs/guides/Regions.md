## 🏗️ JeriCraft Region Management Commands 🛡️

### 🎯 Introduction
Welcome to the JeriCraft Region Management tutorial! 📚 Protecting your builds and managing access to specific areas is
essential for a seamless and enjoyable experience on our server. 💻 In this guide, we'll cover the necessary commands to
help you effectively manage your regions and collaborate with others. 🤝

🔺 **Defining Corners**

To create a region, you must first define its corners. 🌟 Stand at one corner and enter the `/pos1` command. Then, move
to the opposite corner and enter `/pos2`. This will mark the boundaries of your desired protected area. 🔲

🗺️ **Expanding Regions**

Use the expand command to adjust your region vertically:

`expand <vert|<amount> <amount> [reverseAmount] [direction]`

Specify vert to expand vertically.

Include `<amount>` to set the number of blocks to expand. Negative values expand downwards.
Optionally, use `[reverseAmount]` to expand in the opposite direction.

- Use `[direction]` to expand in a specific direction: north, east, south, or west.

Example: `expand vert 10` will expand your region upwards by 10 blocks. 📏

🔐 **Claiming and Removing Regions**

- To claim a region, use `rg claim <rg name>`. Replace `<rg name>` with your desired region name. 🚩
- To remove a region, enter `rg remove <rg name>`. 🔙

📖 **Displaying Region Information**

- Enter `rg i` to view information about the region you're standing in. 📚

📝 **Listing Owned Regions**

- Use `rg list` to display a list of all regions you own. 🗂️

👥 **Adding and Removing Members and Owners**

- To add a member to a region, enter `rg addmember <rg name> <player>`. 👪
- To remove a member, use `rg removemember <rg name> <player>`. 😔
- Add an owner to a region with `rg addowner <rg name> <player>`. 🤴
- Remove an owner using `r`g removeowner <rg name> <player>`. 👑

🔮 **Setting Region Flags**

Customize region settings using `rg flag <rg name> <flag> <value>`. Replace `<flag>` with the desired setting
and `<value>` with the appropriate parameter.

Example: `rg flag myregion mob-spawning deny` will prevent mobs from spawning in the region named "myregion." 🚫

For a list of available region flags, refer to the [Region Flags section](../features/Main.md#worldguard) in the Main
documentation.

🌟 **Conclusion**

We hope this tutorial helps you effectively manage your protected regions on JeriCraft! 💖 Feel free to explore and
experiment with these commands. If you have any questions or need assistance, don't hesitate to ask our friendly
community or server staff. Happy building! 🏠

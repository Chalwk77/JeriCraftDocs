````yml
announcements:
  auctions:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bAuctions &2&l[&8&l=======&7
    Participate in player-driven auctions!
    Learn more with our detailed guide (click here).

    • Useful commands: &b/ah&7, &b/ah help",
      "clickEvent": {
        "action": "open_url",
        "value": "https://github.com/Chalwk77/JeriCraftDocs/blob/main/docs/guides/AuctionHouse.md"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to access our AuctionHouse guide."
      }
    }
  boosts:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bAuto Boosts &2&l[&8&l=======&7
    • &bWeekend Party: &71.25x XP, 1.5x Money (Fri-Sat, 8-11 PM)
    • &bEarly Bird: &71.5x XP, 1.25x Money (Mon-Fri, 6-9 AM)
    • &bMid-Week Motivation: &71.75x XP & Money (Wed, 12-3 PM)
    • &bCrafter's Delight: &72.5x XP, 2x Money (Mon, Wed, Fri, 2-4 PM)
    • &bEnchanter's Empowerment: &73x XP, 1.75x Money (Tue, Thu, Sat, 9-11 PM)
    • &bHunter's Harvest: &72.25x XP, Money (Mon, Wed, Fri, 6-8 PM)
    • &bBuilder's Bonanza: &72x XP, 1.75x Money (Tue, Thu, Sat, 10 AM-1 PM)
    • &bMerchant's Marvel: &71.75x XP, 2x Money (Wed, 3-6 PM)
    • &bMiner's Madness: &72x XP, 1.5x Money (Mon, Wed, Fri, 8-10 PM)
    • &bFarmer's Feast: &72x XP & Money (Tue, Thu, Sat, 6-9 AM)",
      "hoverEvent": {
        "action": "show_text",
        "value": "&eBoosts are active at specific times during the week."
      }
    }
  chest_shop:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bChest Shop Tutorial &2&l[&8&l=======&7
    Need help creating a chest shop?

    •  Click here to view our step-by-step guide.",
      "clickEvent": {
        "action": "open_url",
        "value": "https://github.com/Chalwk77/JeriCraftDocs/blob/main/docs/guides/ChestShop.md"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eCheck out our detailed, step-by-step guide"
      }
    }
  emojis:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bEMOJIS &2&l[&8&l=======&7
    You can use emojis in chat, on signs and in books!

    •  Click to see custom emojis or type &b/emojis",
      "clickEvent": {
        "action": "run_command",
        "value": "/emojis"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to explore our custom emojis collection."
      }
    }
  bookshelves:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bBookshelves &2&l[&8&l=======&7
    Store, display & remove books with ease!

    •  Hold a &bwritten book &7to place on shelf.
    •  Left-click to place or check out a transient copy.
    •  Right-click to view book.
    •  Shift-left-click to remove your book.",
      "hoverEvent": {
        "action": "show_text",
        "value": "&eStore, display & remove books with ease!"
      }
    }
  hats:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bHats &5[members only] &2&l[&8&l=======&7
    Wear any item as a hat with &b/hat &7command!
    Hold an item, type &b/hat &7to wear it.

    Express your style and unlock this &5Members-only &7reward!",
      "clickEvent": {
        "action": "run_command",
        "value": "/hat"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to wear any item as a hat."
      }
    }
  item_recipes:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bItem Recipes &2&l[&8&l=======&7
    •  Click to open the Recipe GUI or type &b/recipe <material name>&7
       to view a visual guide for crafting recipes.",
      "clickEvent": {
        "action": "run_command",
        "value": "/recipe"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to open the Recipe GUI."
      }
    }
  jobs_gui:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bJobs GUI &2&l[&8&l=======&7
    Keep track of your &b&lJOBS &7stats with our custom stats GUI!

    •  Click to open the GUI or type &b/jobs.",
      "clickEvent": {
        "action": "run_command",
        "value": "/jobs"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to open JOBS GUI"
      }
    }
  jobs_guide:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bJobs Guide &2&l[&8&l=======&7
    Jobs pay you for breaking, placing, killing,
    fishing, crafting and more; Gain experience
    as you perform your job.

    •  Click here or type &b/jobs &7for more information.",
      "clickEvent": {
        "action": "open_url",
        "value": "https://github.com/Chalwk77/JeriCraftDocs/blob/main/docs/guides/Jobs.md"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eLearn how to join and use Jobs with our detailed guide."
      }
    }
  mcmmo:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bmcMMO &2&l[&8&l=======&7
    McMMO is a skill system that rewards you with experience
    as you use tools, weapons, and perform various actions.

    Skills are divided into &bGathering&7, &bCombat&7, & &bMiscellaneous&7.
    Gain bonuses like &bdouble drops&7, &brare drops&7,
    and &bability enhancements&7 as you level up.

    •  Click here for our detailed mcMMO guide.",
      "clickEvent": {
          "action": "open_url",
          "value": "https://github.com/Chalwk77/JeriCraftDocs/blob/main/docs/guides/mcMMO.md"
       },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to view our comprehensive mcMMO guide."
      }
    }
  mcmmo_gui:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bMCMMO GUI &2&l[&8&l=======&7
    Keep track of your mcMMO stats with our custom stats GUI!

    •  Click to open the GUI or type &b/mcmmo.",
      "clickEvent": {
        "action": "run_command",
        "value": "/mcmmo"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to open mcMMO GUI."
      }
    }
  member_rank:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bMember Rank &2&l[&8&l=======&7
    Join our Discord Server for &5Member&7 rank!

    •  Click here to view the &binvite link&7 or type &b/discord",
      "clickEvent": {
        "action": "open_url",
        "value": "https://discord.com/invite/vcyM6epaqg"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to join our Discord!"
      }
    }
  playtime_rewards:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bPLAYTIME REWARDS &2&l[&8&l=======&7
    Get rewards for spending time on the server!

    • Hourly: $50, 10 XP levels, full heal
    • 6/12/24 hours: Cash, XP, free heal, rare/epic item
    • Weekly: $5000, 100 XP levels, Totem of Undying
    • Monthly: $10000, 200 XP levels, Shulker Box w/valuable items

    Type &b/prewards &cto see all rewards.&7
    Type &b/playtimetop &cto see top players.",
      "clickEvent": {
        "action": "suggest_command",
        "value": "/prewards"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to learn about our Play Time Rewards."
      }
    }
  portable_ender_chest:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bPortable Ender Chest &2&l[&8&l=======&7
    Access your Ender Chest anywhere!

    •  Click to open your Ender Chest or type &b/ender.",
      "clickEvent": {
        "action": "run_command",
        "value": "/ender"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to open your Ender Chest."
      }
    }
  previous_location:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bPrevious Location &2&l[&8&l=======&7
    Never lose your way!
    Type &b/back &7to return to your previous location.
    Particularly helpful when you respawn.",
      "clickEvent": {
        "action": "run_command",
        "value": "/back"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to instantly return to your previous location."
      }
    }
  region_management:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bRegion Management Guide &2&l[&8&l=======&7
    Looking to manage your regions effectively?

    •  Click here to view our Region Management guide.",
      "clickEvent": {
        "action": "open_url",
        "value": "https://github.com/Chalwk77/JeriCraftDocs/blob/main/docs/guides/Regions.md"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eCheck out our comprehensive Region Management guide."
      }
    }
  scavenge:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bScavenge &2&l[&8&l=======&7
    Salvage items, extract enchantments & reclaim resources!

    •  Click to Scavenge or type &b/scavenge",
      "clickEvent": {
        "action": "run_command",
        "value": "/scavenge"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to Scavenge."
      }
    }
  server_shop:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bServer Shop &2&l[&8&l=======&7
    Need supplies? Go to &b/warp shop&7

    •  Click to fast-travel here.",
      "clickEvent": {
        "action": "run_command",
        "value": "/warp shop"
     },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to fast-travel to the server shop."
      }
    }
  sitting:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bSitting &2&l[&8&l=======&7
    Members can sit in various locations:
    • Right-click on a carpet, stair, or slab block.
    • Use &b/sit &7command to perch anywhere!",
      "clickEvent": {
        "action": "run_command",
        "value": "/sit"
      },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to use the /sit command and perch anywhere."
      }
    }
  slimefun:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bSlimefun &2&l[&8&l=======&7
    Slimefun is a comprehensive plugin that adds
    tech and magic elements to Minecraft, enhancing
    your survival experience with hundreds of hours
    of new content.

    •  Click to discover the wonders of Slimefun with
       our detailed guide here.",
      "clickEvent": {
          "action": "open_url",
          "value": "https://github.com/Chalwk77/JeriCraftDocs/blob/main/docs/guides/Slimefun.md"
       },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to access our in-depth Slimefun guide."
      }
    }
  webstore:
  - |-
    {
      "text": "&8=======&2&l] &c&lINFO: &bPERKS &2&l[&8&l=======&7
    •  Click to visit our webstore to browse and
       purchase unique perks.",
      "clickEvent": {
          "action": "open_url",
          "value": "https://github.com/Chalwk77/JeriCraftDocs/tree/main/docs/webstore"
       },
      "hoverEvent": {
        "action": "show_text",
        "value": "&eClick to explore our webstore for exclusive perks."
      }
    }
```
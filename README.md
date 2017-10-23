# 2B2T: Bot Ignore

## Introduction

A minecraft mod for 2b2t to auto-ignore bots using /ignorehard.  This mod will fetch an updated list every 5 minutes of known bots to ignore.  The object of the master list is to stop spam from useless bots.  Established bots that everyone likes are not in the list.  If you do not like my list, you can use your own.  To change the URL, rebuild the mod with an url link to a text file which contains Minecraft user UUIDs.

## Usage

This mod requires Minecraft Forge

**Release package**
1. Download: https://github.com/CraftyChaos/2b2t-bot-ignore/releases/download/v1.2/botignore-1.2.jar
2. Drop the released .jar into your minecraft mod directory
3. Remove old version if installed

**Build package**
```
git clone https://github.com/CraftyChaos/2b2t-bot-ignore.git
cd 2b2t-bot-ignore

# to edit it eclipse
./gradlew eclipse

# to build
./gradlew build

cp build/libs/botignore.* <path to mineraft mod directory>
```

## TODO

Remove bots from ignorelist if UUIDs are removed from master list.  Priority: Low.

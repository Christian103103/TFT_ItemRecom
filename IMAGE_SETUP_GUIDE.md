# TFT Item Images Setup Guide

This guide will help you download and set up the item images for your TFT tracker.

## Option 1: Use the Tracker Without Images (Quick Start)

The tracker is **already functional** with emoji placeholders! You can use it right away:
- Open `tft-tracker.html` in your browser
- The items display with emojis instead of images
- All functionality works perfectly

## Option 2: Add Official TFT Item Images

If you want the authentic TFT item icons, follow these steps:

### Step 1: Create the Images Folder
1. Create a new folder called `images` in your TFTproj directory
2. Your structure should look like:
   ```
   TFTproj/
   ├── tft-tracker.html
   ├── IMAGE_SETUP_GUIDE.md
   └── images/          (new folder)
   ```

### Step 2: Download Item Icons

You have two options for downloading the icons:

#### Method A: From League of Legends Wiki (Recommended)

1. Visit the [TFT Item Icons category](https://leagueoflegends.fandom.com/wiki/Category:TFT_item_icons)

2. Download each of the following items (right-click on the image and "Save image as..."):

   - **B.F. Sword** → Save as `bf-sword.png`
   - **Recurve Bow** → Save as `recurve-bow.png`
   - **Needlessly Large Rod** → Save as `needlessly-large-rod.png`
   - **Tear of the Goddess** → Save as `tear.png`
   - **Chain Vest** → Save as `chain-vest.png`
   - **Negatron Cloak** → Save as `negatron-cloak.png`
   - **Giant's Belt** → Save as `giants-belt.png`
   - **Sparring Gloves** → Save as `sparring-gloves.png`

3. Place all downloaded images in the `images` folder

#### Method B: From Riot Data Dragon API

1. Visit: https://ddragon.leagueoflegends.com/cdn/13.24.1/img/tft-item/

2. Find and download the base component items

3. Rename them according to the list above and place in the `images` folder

### Step 3: Verify Setup

After downloading the images:
1. Open `tft-tracker.html` in your browser
2. You should see the official TFT item icons instead of emojis
3. If images don't appear, check:
   - File names match exactly (case-sensitive)
   - Images are in the correct `images/` folder
   - Image files are .png format

## Troubleshooting

**Images not showing?**
- Check browser console (F12) for errors
- Verify file paths are correct
- Make sure image files aren't corrupted
- Try refreshing the page (Ctrl+F5)

**Can't find specific items on the wiki?**
- Use the search function on the wiki
- Look for "TFT" or "Teamfight Tactics" versions
- Make sure you're getting base components, not combined items

**Still having issues?**
- The tracker works perfectly with emojis
- You can always add images later
- Try using different image sources

## Alternative: Use Your Own Images

You can use any images you want! Just:
1. Name them according to the list in Step 2
2. Place them in the `images` folder
3. Recommended size: 80x80px or larger
4. Format: PNG with transparent background works best

---

**Quick Start Reminder:** The tracker works immediately without images - just open the HTML file!

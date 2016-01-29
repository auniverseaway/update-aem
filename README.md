### What this does
Deploys desired hotfixes to an AEM instance.

### Requirements
1. A running AEM instance
2. Ability to download AEM hotfixes, feature packs, etc.

### Usage
1. Configure the ```updateaem``` file with your AEM server's details
2. Ensure updateaem is executeable ```chmod +x updateaem```
3. Add your packages to the packages folder. *Important:* The script executes by modified date.
4. Run the script ```./updateaem```

### Credits
Based in part on this [blog post](http://labs.6dglobal.com/blog/2016-01-08/installing-aem61-hotfixes/)
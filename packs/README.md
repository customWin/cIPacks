# Publishing an icon pack

Publishing an icon pack is easy, but you should know these:

## Prerequisites
* An icon pack with an manifest in a .cIPack file
* If you are redistributing icons, you need also a permission from the author 

## Steps
1. Fork this repo
2. Upload your file in this folder
3. Add this to the `cIPackStore.json` file:
```json
,{
   "name": "My cool pack",
   "description": "This is a cool icon pack that you should use.",
   "author": "jbcarreon123",
   "icon_author": "jbcarreon123"
   "filename": "my cool pack.cIPack"
}
```
4. Create a pull request to this repo

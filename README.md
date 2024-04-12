# Scol

### FAQ

1. **Q**: `Automatic merge failed; fix conflicts and then commit the result.`    
   **A**: remove scol bucket and add it again. `scoop bucket rm scol && scoop bucket add scol https://github.com/Kosette/scol.git`

2. **Q**: cannot install latest package or anything else about updating packages     
   **A**: uninstall package and reinstall. `scoop uninstall [package] && scoop update && scoop install [package]`
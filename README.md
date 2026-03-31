
# IrfanView_AppImage

IrfanView is an image viewer, editor, organizer and converter

https://www.irfanview.com/

## Repository: https://github.com/ryuuzaki42/IrfanView_AppImage

---
### To change font size, change the DPI value in LogPixels
In the user.reg in `~/.config/IrfanView_AppImage/IrfanView/user.reg`

At the end of block `[Control Panel\\Desktop]`

### Added LogPixels with desire value

#### To 100% text size
`"LogPixels"=dword:00000060`

#### To 125% text size
`"LogPixels"=dword:00000090`

#### To 150% text size
`"LogPixels"=dword:000000144`

---
https://www.irfanview.com/64bit.htm

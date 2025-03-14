# winget-windows-repo
Winget is a command-line tool, and the client interface for the Windows Package Manager, allowing users to discover, install, upgrade, remove, and configure applications on Windows 10, 11, and Windows Server 2025 computers

### Download youtube videos use to winget

- [yt-dlp - Github link](https://github.com/yt-dlp/yt-dlp?tab=readme-ov-file)

```
winget search yt-dlp
winget install yt-dlp
```

```
1. yt-dlp -f "bestvideo[height=720]+bestaudio" "Video Link"
2. .\yt-dlp.exe -f "bestvideo[height=720]+bestaudio" "Video link"
3. "C:\Users\Shahnwaz Aalam\AppData\Local\Microsoft\WinGet\Packages\yt-dlp.yt-dlp_Microsoft.Winget.Source_8wekyb3d8bbwe\yt-dlp.exe" -f "bestvideo[height=720]+bestaudio" "https://youtu.be/hGcH2WUMODw"

Set Path
4. setx PATH "%PATH%;C:\Users\Shahnwaz Aalam\AppData\Local\Microsoft\WinGet\Packages\yt-dlp.yt-dlp_Microsoft.Winget.Source_8wekyb3d8bbwe"


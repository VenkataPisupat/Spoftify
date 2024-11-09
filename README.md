<h1>System requirements</h1>

- <strong>OS: Windows 7-11</strong>
- <strong>Spotify: latest official [versions](https://docs.google.com/spreadsheets/d/1Vc5PAWC41ji8IuC4LXCTzf_H3vd_SVABEsabRnACCw8/edit?usp=sharing)</strong>
- <strong>For Windows Desktop only (Microsoft store version is not suitable).</strong>
- <strong>PowerShell: version 5 and above recommended</strong>

<h1>Features</h1>

- <strong>Blocks all banner, video and audio ads in the client</strong>
- <strong>Hiding podcasts, episodes and audiobooks from the homepage (optional)</strong>
- <strong>Block Spotify automatic updates (optional)</strong>
- <strong>Disabled sentry's console log/error/warning messages to Spotify developers, halted user interaction logging, eliminated right-to-left CSS rules for simplification, and performed code minification</strong> 

<h1>Fast installation / Update</h1>
<h3>Choose installation type:</h3>
<details>
<summary><small>Usual installation (New theme)</small></summary><p>
  
  #### During installation, you need to confirm some actions, also contains:
  
  - New theme activated (new right and left sidebar, some cover change)

  <h4> </h4>
  
#### Just download and run [Install.bat](https://raw.githack.com/amd64fox/SpotX/main/Install_New_theme.bat)

or

#### Run The following command in PowerShell:

```ps1
iex "& { $(iwr -useb 'https://raw.githubusercontent.com/SpotX-Official/spotx-official.github.io/main/run.ps1') } -new_theme"
```

#### mirror

```ps1
iex "& { $(iwr -useb 'https://spotx-official.github.io/run.ps1') } -m -new_theme"
```

</details>
  

<details>
<summary><small>Usual installation (Old theme)</small></summary><p>
  
  #### During installation, you need to confirm some actions, also contains:
  - Forced installation of version 1.2.13 (since the old theme was removed in subsequent versions)
  - Old theme activated
  - Automatic blocking of Spotify updates
  <h4> </h4>
  
#### Just download and run [Install.bat](https://raw.githack.com/amd64fox/SpotX/main/Install_Old_theme.bat)

or

#### Run The following command in PowerShell:

```ps1
iex "& { $(iwr -useb 'https://raw.githubusercontent.com/SpotX-Official/spotx-official.github.io/main/run.ps1') } -v 1.2.13.661.ga588f749-4064 -confirm_spoti_recomended_over -block_update_on"
```

#### mirror

```ps1
iex "& { $(iwr -useb 'https://spotx-official.github.io/run.ps1') } -m -v 1.2.13.661.ga588f749-4064 -confirm_spoti_recomended_over -block_update_on"
```

</details>
 
<details>
<summary><small>Full installation</small></summary><p>
  
  <h4>Full installation without confirmation, what does it do?</h4> 
  
  - New theme activated (new right and left sidebar, some cover change)
  - Hiding podcasts/episodes/audiobooks from the homepage
  - Removal of Spotify MS if it was found 
  - Installation of the recommended version of Spotify (if another client has already been found, it will be installed over) 
  - Blocking of Spotify updates
  - After the installation is completed, the client will autorun.
  
<h4> </h4>

#### Just download and run [Install_Auto.bat](https://raw.githack.com/amd64fox/SpotX/main/scripts/Install_Auto.bat)

or

#### Run The following command in PowerShell:

```ps1
iex "& { $(iwr -useb 'https://raw.githubusercontent.com/SpotX-Official/spotx-official.github.io/main/run.ps1') } -confirm_uninstall_ms_spoti -confirm_spoti_recomended_over -podcasts_off -block_update_on -start_spoti -new_theme -adsections_off -lyrics_stat spotify"
```

#### mirror

```ps1
iex "& { $(iwr -useb 'https://spotx-official.github.io/run.ps1') } -m -confirm_uninstall_ms_spoti -confirm_spoti_recomended_over -podcasts_off -block_update_on -start_spoti -new_theme -adsections_off -lyrics_stat spotify"
```

</details>

<details>
<summary><small>Other types of installations</summary><p>

<details>
<summary><small>Installation for premium</small></summary><p>
  
  #### Usual installation only without ad blocking, for those who have a premium account, also contains:
  
  - New theme activated (new right and left sidebar, some cover change)
  - Disabled only audio ads in podcasts

  <h4> </h4>
  
#### Just download and run [Install_Prem.bat](https://raw.githack.com/amd64fox/SpotX/main/scripts/Install_Prem.bat)

or

#### Run The following command in PowerShell:

```ps1
iex "& { $(iwr -useb 'https://raw.githubusercontent.com/SpotX-Official/spotx-official.github.io/main/run.ps1') } -premium -new_theme"
```

#### mirror

```ps1
iex "& { $(iwr -useb 'https://spotx-official.github.io/run.ps1') } -m -premium -new_theme"
```


<h1>Uninstall</h1>

- Just run [Uninstall.bat](https://raw.githack.com/amd64fox/SpotX/main/Uninstall.bat)

or

- Reinstall Spotify ([Full uninstall Spotify](https://github.com/amd64fox/Uninstall-Spotify) recommended)

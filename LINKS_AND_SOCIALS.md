# AppleMusicPlus - Links, Socials & Credits Directory

Yeh document AppleMusicPlus project me use hone wale sabhi social media accounts, Telegram, Instagram, GitHub profiles/repositories, upstream open-source projects, APIs aur third-party services ki poori jaankari table ke roop me provide karta hai.

---

## 1. Developers & Maintainers (Official Social Media)

| Name / Handle | Platform / Service | Link / Target URL | File Location & Reference | Description / Role |
| :--- | :--- | :--- | :--- | :--- |
| **Ritesh** | **Instagram** | [https://www.instagram.com/shivangmishraxx](https://www.instagram.com/shivangmishraxx) | `app/src/main/kotlin/com/mochyy/mochymusic/core/updater/GithubUpdates.kt` (`InstagramUrl`)<br>`app/src/main/kotlin/com/mochyy/mochymusic/ui/screens/settings/devspace/DevProfiles.kt` | Official Instagram handle (@shivangmishraxx) |
| **Ritesh** | **Telegram** | [https://t.me/theshivxd](https://t.me/theshivxd) | `app/src/main/kotlin/com/mochyy/mochymusic/core/updater/GithubUpdates.kt` (`TelegramUrl`)<br>`app/src/main/kotlin/com/mochyy/mochymusic/ui/screens/settings/ProfileScreen.kt`<br>`app/src/main/kotlin/com/mochyy/mochymusic/ui/screens/settings/devspace/DevProfiles.kt` | Official Telegram channel / handle (@theshivxd) |
| **TheAloneTeam** | **GitHub Organization** | [https://github.com/TheAloneTeam](https://github.com/TheAloneTeam) | `app/src/main/kotlin/com/mochyy/mochymusic/core/updater/GithubUpdates.kt` (`GithubOwner`, `GithubProfileUrl`)<br>`app/src/main/kotlin/com/mochyy/mochymusic/ui/screens/update/AboutSheet.kt` | Official GitHub organization |
| **AppleMusicPlus** | **GitHub Repo** | [https://github.com/TheAloneTeam/AppleMusicPlus](https://github.com/TheAloneTeam/AppleMusicPlus) | `app/src/main/kotlin/com/mochyy/mochymusic/core/updater/GithubUpdates.kt` (`GithubRepoUrl`)<br>`app/src/main/kotlin/com/mochyy/mochymusic/ui/screens/update/AboutSheet.kt` | Official source code repository |

---

## 2. Removed Links (Removed as per requirements)

Yeh sabhi services aur platforms app aur repository se hta diye gaye hain:
- **Threads** (Removed)
- **Ko-fi** (Removed)
- **SociaBuzz** (Removed)
- **Buy Me a Coffee** (Removed)
- **Discord Server / Mochy's Bar** (Removed)
- **Figma Roadmap** (Removed)
- **Trendshift** (Removed)

---

## 3. Upstream Projects & Base Credits

AppleMusicPlus in open-source projects ke upar adharit ya unse inspired hai:

| Project Name | Author / Maintainer | GitHub Repository / Website | License | Role / Purpose |
| :--- | :--- | :--- | :--- | :--- |
| **ViviMusic** | vivizzz007 / vivizzz007Z | [https://github.com/vivizzz007/vivi-music](https://github.com/vivizzz007/vivi-music) | GPL-3.0 | Base application project |
| **Metrolist** | Mostafa Alagamy (`mostafaalagamy`) | [https://github.com/mostafaalagamy/Metrolist](https://github.com/mostafaalagamy/Metrolist) | GPL-3.0 | Base framework architecture |
| **SimpMusic** | maxrave-dev (`maxrave-dev`) | [https://github.com/maxrave-dev/SimpMusic](https://github.com/maxrave-dev/SimpMusic) | GPL-3.0 | Lyrics API provider integration |
| **ArchiveTune** | Rukamori (`rukamori`) | [https://github.com/rukamori/ArchiveTune](https://github.com/rukamori/ArchiveTune) | GPL-3.0 | UI/UX design & architecture inspiration |
| **RiMusic / InnerTube** | fast4x (`fast4x`) | [https://github.com/fast4x/RiMusic](https://github.com/fast4x/RiMusic) | GPL-3.0 | YouTube Music InnerTube API service wrapper |
| **LRCLIB** | tranxuanthang (`tranxuanthang`) | [https://github.com/tranxuanthang/lrclib](https://github.com/tranxuanthang/lrclib) | MIT | Synchronized LRC lyrics provider |
| **AutoEq** | Jaakko Pasanen (`jaakkopasanen`) | [https://github.com/jaakkopasanen/AutoEq](https://github.com/jaakkopasanen/AutoEq) | MIT | Headphone equalizer profiles database |

---

## 4. Source Code Constants & File References

```kotlin
// File: app/src/main/kotlin/com/mochyy/mochymusic/core/updater/GithubUpdates.kt
const val GithubOwner = "TheAloneTeam"
const val GithubRepo = "AppleMusicPlus"
const val GithubProfileUrl = "https://github.com/$GithubOwner"
const val GithubRepoUrl = "https://github.com/$GithubOwner/$GithubRepo"
const val InstagramUrl = "https://www.instagram.com/shivangmishraxx"
const val TelegramUrl = "https://t.me/theshivxd"
```

# Terminal Music Player

[中文自述](#中文自述) | [English README](#english-readme)

---

## 中文自述

### 终端风格音乐播放器

这是一个具有黑客帝国风格的网页音乐播放器，采用终端界面设计理念，结合了绿色代码雨背景和现代播放器功能。

#### 主要功能

1. **酷炫视觉效果**
   - 黑客帝国风格的字符雨背景
   - 音频频谱可视化显示
   - 霓虹灯边框和发光效果

2. **音乐播放功能**
   - 支持从本地文件夹加载音乐文件
   - 播放控制（播放/暂停、上一曲、下一曲）
   - 进度条拖放控制
   - 歌曲信息显示（标题、艺术家）

3. **歌词系统**
   - 自动匹配本地.lrc歌词文件
   - 在线歌词搜索（通过lyrics.ovh API）
   - 歌词同步高亮显示
   - 支持点击歌词跳转播放位置

4. **智能文件处理**
   - 自动从文件名解析歌曲元数据
   - 支持多种分隔符（"-", "_", "by", "•"）
   - 歌词文件智能匹配系统

5. **响应式设计**
   - 适配桌面和移动设备
   - 窗口大小变化时自动调整布局

#### 使用方法

1. 点击"Open Folder"按钮选择包含音乐文件的文件夹
2. 在播放列表中选择要播放的歌曲
3. 使用播放控制按钮管理播放
4. 点击频谱可视化区域可查看动态音频效果
5. 点击歌词可跳转到相应播放位置

#### 技术细节

- 使用HTML5 Audio API进行音频处理
- Web Audio API实现频谱可视化
- Canvas实现字符雨背景效果
- 文件API读取本地音乐和歌词文件
- 响应式CSS布局适配不同设备

#### 系统要求

- 现代浏览器（Chrome、Firefox、Edge最新版）
- 支持Web Audio API和Canvas

---

## English README

### Terminal-Style Music Player

A hacker-themed web music player with terminal-inspired interface, featuring green code rain background and modern player functionalities.

#### Key Features

1. **Immersive Visuals**
   - Matrix-style character rain background
   - Audio spectrum visualizer
   - Neon borders and glow effects

2. **Music Playback**
   - Load music files from local folders
   - Playback controls (play/pause, previous, next)
   - Draggable progress bar
   - Track information display (title, artist)

3. **Lyrics System**
   - Automatic matching of local .lrc files
   - Online lyrics search (via lyrics.ovh API)
   - Synchronized lyric highlighting
   - Click lyrics to jump to playback position

4. **Smart File Processing**
   - Automatic metadata extraction from filenames
   - Support for multiple separators ("-", "_", "by", "•")
   - Intelligent lyric file matching

5. **Responsive Design**
   - Adapts to desktop and mobile devices
   - Automatic layout adjustment on window resize

#### How to Use

1. Click "Open Folder" to select a folder with music files
2. Select a track from the playlist
3. Use playback controls to manage playback
4. View dynamic audio effects in the visualizer
5. Click lyrics to jump to specific playback positions

#### Technical Details

- HTML5 Audio API for audio processing
- Web Audio API for spectrum visualization
- Canvas for character rain effect
- File API for local file access
- Responsive CSS layout

#### System Requirements

- Modern browser (latest Chrome, Firefox, Edge)
- Web Audio API and Canvas support

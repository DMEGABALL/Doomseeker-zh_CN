# 第三方组件与许可证说明

本项目的汉化部分（翻译文件、构建集成改动）以 **GNU LGPL v2.1-or-later** 发布。
源码目录中的 Doomseeker 代码版权归其原作者所有，同样遵循 LGPL v2.1-or-later，详见 `LICENSE`。

便携版（Doomseeker-zh_CN-1.5.3-win64-portable.zip）包含以下未修改的第三方运行库，
其版权与许可证归各自作者所有。所有 DLL 均可由用户自行替换为兼容版本。

## 主要组件

| 组件 | 许可证 | 获取源码 |
|---|---|---|
| Doomseeker 1.5.3 | LGPL-2.1-or-later | 本仓库 `source/`；上游 https://github.com/DoomseekerTeam/Doomseeker |
| Qt 6.12（Core/Gui/Widgets/Network/Xml/Multimedia 及插件、翻译） | LGPL-3.0（或 GPL-3.0 / 商业许可） | https://download.qt.io/ ；MSYS2：https://packages.msys2.org/ |
| FFmpeg 运行库（avcodec/avformat/avutil/swscale/swresample） | LGPL-2.1-or-later（构建可能包含 GPL 组件，以实际构建为准） | https://ffmpeg.org/ ；MSYS2 同名软件包 |
| 其他运行库（HarfBuzz、FreeType、ICU、libpng、zlib、libjpeg-turbo、libwebp、Pango、GLib、GnuTLS、OpenSSL 等） | 各自的开源许可证 | 见下方清单对应的 MSYS2 软件包：https://packages.msys2.org/ |

许可证全文见 `LICENSES/LGPL-3.0.txt`、`LICENSES/GPL-3.0.txt`；上游 LGPL-2.1 全文见 `LICENSE`。

> 说明：便携版由 MSYS2 的 mingw-w64 软件包构建。若需重新链接 Qt 或其他库，
> 可直接用同名 DLL 替换（这些库未被修改），或按上述地址获取源码自行构建。

## 便携版中的 Qt 组件

- Qt6Core.dll
- Qt6Gui.dll
- Qt6Multimedia.dll
- Qt6Network.dll
- Qt6Widgets.dll
- Qt6Xml.dll

## 便携版中的 Doomseeker 插件

- engines/libchocolatedoom.dll
- engines/libodamex.dll
- engines/libturok2ex.dll
- engines/libzandronum.dll
- engines/libzandronumq.dll

## 便携版中的其他第三方 DLL

- avcodec-63.dll
- avformat-63.dll
- avutil-61.dll
- generic/qtuiotouchplugin.dll
- imageformats/qgif.dll
- imageformats/qico.dll
- imageformats/qjpeg.dll
- libLerc.dll
- libSvtAv1Enc-4.dll
- libaom.dll
- libb2-1.dll
- libbluray-4.dll
- libbrotlicommon.dll
- libbrotlidec.dll
- libbrotlienc.dll
- libbz2-1.dll
- libcairo-2.dll
- libcairo-gobject-2.dll
- libcrypto-4-x64.dll
- libdatrie-1.dll
- libdav1d-7.dll
- libdeflate.dll
- libdouble-conversion.dll
- libexpat-1.dll
- libffi-8.dll
- libfontconfig-1.dll
- libfreetype-6.dll
- libfribidi-0.dll
- libgcc_s_seh-1.dll
- libgdk_pixbuf-2.0-0.dll
- libgio-2.0-0.dll
- libglib-2.0-0.dll
- libgme.dll
- libgmodule-2.0-0.dll
- libgmp-10.dll
- libgnutls-30.dll
- libgobject-2.0-0.dll
- libgomp-1.dll
- libgraphite2.dll
- libgsm.dll
- libharfbuzz-0.dll
- libhogweed-7.dll
- libhwy.dll
- libiconv-2.dll
- libicudt78.dll
- libicuin78.dll
- libicuuc78.dll
- libidn2-0.dll
- libintl-8.dll
- libjbig-0.dll
- libjpeg-8.dll
- libjxl.dll
- libjxl_cms.dll
- libjxl_threads.dll
- liblc3-1.dll
- liblcms2-2.dll
- liblzma-5.dll
- libmd4c.dll
- libmodplug-1.dll
- libmp3lame-0.dll
- libmpg123-0.dll
- libnettle-9.dll
- libogg-0.dll
- libopencore-amrnb-0.dll
- libopencore-amrwb-0.dll
- libopenjp2-7.dll
- libopus-0.dll
- libp11-kit-0.dll
- libpango-1.0-0.dll
- libpangocairo-1.0-0.dll
- libpangoft2-1.0-0.dll
- libpangowin32-1.0-0.dll
- libpcre2-16-0.dll
- libpcre2-8-0.dll
- libpixman-1-0.dll
- libpng16-16.dll
- librav1e.dll
- librsvg-2-2.dll
- librtmp-1.dll
- libsharpyuv-0.dll
- libsoxr.dll
- libspeex-1.dll
- libsrt.dll
- libssh.dll
- libstdc++-6.dll
- libtasn1-6.dll
- libthai-0.dll
- libtheoradec-2.dll
- libtheoraenc-2.dll
- libtiff-6.dll
- libunistring-5.dll
- libva.dll
- libvorbis-0.dll
- libvorbisenc-2.dll
- libvpl-2.dll
- libvpx-1.dll
- libwebp-7.dll
- libwebpmux-3.dll
- libwinpthread-1.dll
- libx264-165.dll
- libx265-217.dll
- libxml2-16.dll
- libzstd.dll
- libzvbi-0.dll
- multimedia/ffmpegmediaplugin.dll
- networkinformation/qglib.dll
- networkinformation/qnetworklistmanager.dll
- platforms/qwindows.dll
- styles/qmodernwindowsstyle.dll
- swresample-7.dll
- swscale-10.dll
- tls/qcertonlybackend.dll
- tls/qschannelbackend.dll
- xvidcore.dll
- zlib1.dll

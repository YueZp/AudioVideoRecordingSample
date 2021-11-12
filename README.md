此项目的侧重点在于 Android 音视频相关 API 的使用，尤其是在 录制和编码方面的。

该项目运行后能够将 Camera 采集的视频和音频内容编码成一个 MP4 文件。

这其中用到了 MediaCodec 做编码，用到了 MediaMuxer 将音频和视频混合。

这样的一个完整示例对于掌握 Android 上音视频相关 API 帮忙非常大，因为它能够成功正确运行，而且可以通过去修改其源码来做自己的实验，验证自己对于 API 的理解和掌握。

当你能够熟练掌握其内容，或者你就可以试着更进一步，尝试用 FFmpeg 做音视频的编码和混合，实现和 Android 音视频 API 一样的功能。

AudioVideoRecordingSample
=========================

Simultaneous audio and video recording sample using MediaCodec/MediaMuxer

Copyright (c) 2014-2016 saki t_saki@serenegiant.com

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.

All files in the folder are under this Apache License, Version 2.0.

=========

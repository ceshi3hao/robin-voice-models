# 知更鸟双模型实验

中文说话使用钱琛台词，GPT-SoVITS v2ProPlus；歌曲音色使用 Chevy 演唱，Seed-VC 44.1kHz F0 条件扩散模型。两套素材分开。没有使用 RVC 或 Demucs，人声分离使用 UVR MDX。

语音素材筛选为 524 段训练、25 段独立留出，SoVITS 30轮、GPT 20轮。歌曲素材来自两首歌的商业混音分离，并非录音棚干声，训练 1500 步，采用连续留出区间比较检查点。

翻唱模型需要导唱音频，不直接接受 OpenUtau 工程或 MIDI。项目提供实验模型，不保证主观音质、中文识字率或优于底模。解码、有限数值、压缩包完整性及哈希校验不能代替听审。

数据来源：https://huggingface.co/datasets/simon3000/starrail-voice ，歌曲来源与处理记录见素材包和模型说明。

代码来源：https://github.com/RVC-Boss/GPT-SoVITS 、https://github.com/Plachtaa/seed-vc 。

状态：训练任务正在执行，正式交付文件以 Releases 为准。

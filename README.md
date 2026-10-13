<img width="2098" height="1789" alt="1" src="https://github.com/user-attachments/assets/0f07dff1-a1d8-4b83-89d9-3d9b0776e3a9" />
-专门为windows设计的杜比MAT格式信号发生器，而不是传统的声道测试音轨。

-基于对象的7.1.4声道测试，需要安装Dolby Access，需要HDMI连接（直通、earc转发、分离器转发均可）支持杜比MAT的电视/音响作为默认音频设备，且输出格式设为Dolby Atmos For Home theater。

-默认测试音为正弦波发生器440Hz，可以调频率。也可以用wav文件，附带一个12秒的测试wav，如果你需要真实的声音表现可以用它测试，程序没有停止键，直接关闭即可。

-但不管怎么选，LFE声道测试仅使用正弦波测试。

注意：测试时，会遇到开头声音断续的问题，这就是windows静音机制的一个问题，也是苹果在AppleTV中加入Continuous Audio Connection设计的原因，

可以尝试使用SoundKeeper，比如在windows的启动项里放入并改名为SoundKeeperSineF10A5.exe。

--------------------------
A Dolby MAT format signal generator designed specifically for Windows, rather than traditional channel test tracks.

Object-based 7.1.4 channel testing. Requires Dolby Access to be installed and an HDMI connection (direct pass-through, eARC forwarding, or splitter forwarding are all acceptable). A TV/audio system that supports Dolby MAT must be set as the default audio device, and the output format must be set to Dolby Atmos for Home Theater.

The default test tone is a 440 Hz sine wave generator, and the frequency is adjustable. You can also use WAV files; a 12-second test WAV is included. If you need realistic sound reproduction, you can use it for testing. The program has no stop button; just close it.

However, no matter what you choose, the LFE channel test uses only the sine wave.

Note: During testing, you may encounter audio cutting in and out at the beginning. This is an issue with Windows' audio-silence mechanism, and it is also why Apple added the Continuous Audio Connection design to Apple TV.

You can try using SoundKeeper, for example by placing it in the Windows startup items and renaming it to SoundKeeperSineF10A5.exe.

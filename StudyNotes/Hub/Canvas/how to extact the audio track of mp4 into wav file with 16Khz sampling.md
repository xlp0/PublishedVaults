Here is the command to extract the audio track of an MP4 file into a WAV file with 16kHz data sampling using ffmpeg:

```
ffmpeg -i input.mp4 -acodec pcm_s16le -ac 1 -ar 16000 output.wav
```

Here is a breakdown of the command:

- `ffmpeg` is the ffmpeg command-line tool.
- `-i input.mp4` specifies the input MP4 file.
- `-acodec pcm_s16le` specifies the audio codec to use. In this case, we are using PCM_S16LE, which is a 16-bit linear PCM audio codec.
- `-ac 1` specifies the number of audio channels. In this case, we are extracting a single-channel audio track.
- `-ar 16000` specifies the audio sample rate. In this case, we are using 16kHz.
- `output.wav` specifies the output WAV file.

You can also use the following command to extract the audio track of an MP4 file into a WAV file with 16kHz data sampling without specifying the output file name:

```
ffmpeg -i input.mp4 -acodec pcm_s16le -ac 1 -ar 16000 -vn
```

The `-vn` option tells ffmpeg to not output a video track.
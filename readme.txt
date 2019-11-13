FFmpeg Video Encoder

This software encode YUV420P raw data to video bitstream (Such as H.264, H.265, VP8, MPEG2 etc).
It's the simplest video encoding software based on FFmpeg. 
It contains following project:
simplest_ffmpeg_video_encoder: Simplest video encoder. It uses libavcodec to encode video and uses libavformat to add container format to the video bitstream.
simplest_ffmpeg_video_encoder_pure: Pure video encoder. It only uses libavcodec to encode video (without libavformat).
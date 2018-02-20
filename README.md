# pi_timelapse

create video from images
ffmpeg -pattern_type glob -framerate 12 -i 'img*-*-*-*-*-*.jpg' -c:v libx264 -pix_fmt yuv420p video.mp4


This is a python lib for manipulation and information extraction from videos.


EXAMPLES OF USE:

from boreal import Video
video = Video(path_to_video)
video.path #returns the path from video
video.mimetype #returns the mimetype from video
video.size #returns the dimensions from video
video.duration #returns the duration from video
video.fps #return the FPS from video
video.number_frames #reuturn the number of frames from video
video_converted = video.convert_to(output_format) #This method returns a converted video to the specified format
frame = video.frame_at(number_or_instant_from_frame) #Return a PIL Image from number or instant indicated
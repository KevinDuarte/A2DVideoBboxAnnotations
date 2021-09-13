The bounding box annotations for A2D are in the json file a2d_bounding_box_annotations.json. They are a dictionary in the following format:

{
'$video_name$': [{
    'sentence': _, 
    'instance': _, 
    'boxes': {
        '$frame$': (x, y, w, h)
        }
    }]
}

$video_name$ is the name of the video.
$frame$ is the index of a given frame in the video, within the range [0, n_frames-1]. 

The bounding boxes are represented by their top left point (x, y) and their width/height (w, h).




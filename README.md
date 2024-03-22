# Terrain Classifier for the Spot Quadrupedal Mobile Robot

<p align="center">
    <a href="http://www.youtube.com/watch?v=VEtKG984fVE">
        <img src="http://img.youtube.com/vi/VEtKG984fVE/0.jpg" alt="Terrain Classification Video">
    </a>
</p>

<p align="center">
  <a href="http://www.youtube.com/watch?v=VEtKG984fVE" class="video-link">
    <img src="http://img.youtube.com/vi/VEtKG984fVE/0.jpg" alt="Terrain Classification Video" class="thumbnail">
    <div class="play-button"></div>
  </a>
</p>

<style>
  .video-link {
    position: relative;
    display: inline-block;
  }

  .thumbnail {
    display: block;
    width: 100%;
    height: auto;
    border: none;
  }

  .play-button {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 64px;
    height: 64px;
    background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 64 64" fill="rgba(255, 255, 255, 0.8)"><polygon points="25.571,20.999 25.571,42 42.429,31.5" fill="#ffffff"/><path d="M32,8C17.6,8,6,19.6,6,34s11.6,26,26,26s26-11.6,26-26S46.4,8,32,8z M26,42V22l14,10L26,42z"/></svg>');
    background-size: cover;
    cursor: pointer;
  }
</style>


## TODO
- [ ] Add terrain classification code
- [ ] Add bags?
- [ ] Organize repository


## Paper Details
- **Title:** Terrain Classification for the Spot Quadrupedal Mobile Robot Using Only Proprioceptive Sensing
- **Authors:** Sophie Villemure, Jefferson Silveira, Joshua A. Marshal.
- **Conference:** Submitted to IEEE CCECE 2024 (under review)
- **Year:** 2024

## Citation
    TBA
 
### Abstract
Quadrupedal mobile robots can traverse a wider range of terrain types than their wheeled counterparts but do not perform the same on all terrain types. These robots are prone to undesirable behaviours like sinking and slipping on challenging terrains. To combat this issue, we propose a terrain classifier that provides information on terrain type that can be used in robotic systems to create a traversability map to plan safer paths for the robot to navigate. The work presented here is a terrain classifier developed for a Boston Dynamics Spot robot. Spot provides over 100 measured proprioceptive signals describing the motions of the robot and its four legs (e.g., foot penetration, forces, joint angles, etc.). The developed terrain classifier combines dimensionality reduction techniques to extract relevant information from the signals and then applies a classification technique to differentiate terrain based on traversability. In representative field testing, the resulting terrain classifier was able to identify three different terrain types with an accuracy of approximately 97%.

## Additional Material
- [Paper link: TBA](TBA)
- [Video link](http://www.youtube.com/watch?v=VEtKG984fVE)





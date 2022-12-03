# AprilTag16h5

This repo houses 16h5 [AprilTags](https://april.eecs.umich.edu/software/apriltag) that are `6in x 6in` designed to be printed on a standard `8.5in x 11in` sheet of paper with any printer.

<img src="https://i.imgur.com/rcowUr5.png" alt="Demo tag page." width="250"></img>

### Printing Instructions
To ensure the tags come out as intended ensure the following are correct before printing:
* Grayscale / Black & White
* No "Save ink/toner"
* Print on one side
* No margin
* 100% scale, no "fit", "fit to paper size", "fit to printable area", or "shrink oversized pages"

After printing, measure from the outer edges of the tag that it is infact 6in x 6in.

### File Structure
* `./pdf/` Contains scaled tag images to an `8.5in x 11in` pdf, 1 tag per file.
* `./png/` Contains the original 16h5 tags from the [AprilTag repo](https://github.com/AprilRobotics/apriltag-imgs/tree/master/tag16h5).
* `AprilTag16h5-Combined.pdf` The combined file containing all 30 16h5 tags, the tags are labeled.
  * Tag 0 is not missing, it is on page 30.
* `AprilTag16h5.psd` The Photoshop document used to scale the original `8px x 8px` tags to `8.5in x 11in`.
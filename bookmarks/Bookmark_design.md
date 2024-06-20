# Bookmark design history

In this document, we will detail the different versions of the bookmark design.

## Introduction

We aimed to offer goodies that are not only appealing and memorable but also **environmentally responsible**.
Our goal is to design promotional items that are both useful and durable, aligning with the values of sustainability and environmental respect.
To achieve this objective, we have chosen to create eco-friendly bookmarks.
In addition to their daily utility, bookmarks are items that can convey important messages while remaining practical.
However, for them to be truly durable, it is essential to design them with solid, high-quality materials.

In this introduction, we will detail our initial thoughts regarding the content, size, and materials to be used for our bookmarks.

The first question was about the size of the bookmark, after some research we discovered that they are traditionally 3 sizes of bookmark.
The standard sizes of a bookmark are 55 x 173 mm, 50 x 150 mm or for larger ones 52 x 210 mm.
We choose 50 x 150 mm because it will be easier to do several at the same time.

Our first idea was to demonstrate the capabilities of our machine, showcasing both engraving and cutting features.
Additionally, we wanted to incorporate 

- symbols of Berlin (for the local touch)
- logo of the Technical University of Berlin
- logo of the Open.Make project
- extra text about the event and or the user.

We chose the Berlin skyline with its iconic landmarks. (source ?)
We chose a font similar to that of the Technical University of Berlin to maintain a cohesive aesthetic for the text (font =?).

By combining these elements, we aim to create a bookmark that is not only functional and durable but also a beautiful memento of the Long Night of Sciences in Berlin.

## version 1: engraving tests

### On canva

![image1]()

After finding out about the long night of science, it turns out that there are no German-speaking people.
We therefore decided to remove the part in English.

![image2]()

### On Inkscape

We then went to Inkscape to transform the file into the .svg format needed by the software transforming the design into a Gcode (visicut).
We take the opportunity to change the font for finer letters and for a Berlin skyline with only the main elements.

### laser cut

We first try to use the "engrave" settings, but the results were not satisfactory, and it took too long (15 minutes):
![image3]()



We therefore decided to  use the cut settings, which is faster. It yielded better result, but we had to change the design

## Version 2

### On inkscape

For cutting we had to modify the Open.Make logo, so that the inside of the letters are visible.

The Berlin skyline also weakened the paper resistance (it would break easily), so we  created bridges by erasing some lines.



### Laser cut

We had to try different settings as it is quite unusual to cut paper. We also had issues of the paper being burned on the back side if the power is too high. We put a piece of wood and tape the paper to it for the cut. We tested a cut of multiple paper at once, but the burning marks were too strong and we then went for one paper at a time.

After some tests, we realized that the minimum power to mark the paper was 8%.
We then tested different speed:

- speed at 2%: everything is cut without trace of smoke (clean line)

- speed at 3%: the paper is marked and it can be cut with a little force (clean line)

- speed at 4%: the paper is marked and can not be cut (somewhat fast speed for clear results).




## Known issues

- For the moment the bookmark is quite fragile due to the "Fersehturm" in the skyline, we may add bridges in a future version.
- The font is not `stencilized` and loose some part (in `e` and `o `).

![image4]()

## Bibliographie

[1] TU-berlin-logo.svg

[2] Logo Open.make

[3] Canva/illustration/berlin/free

[4] Silhouette_Berlin.svg

Made by Lucie LAQUIEZE

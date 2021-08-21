I have challenged myself to learning the free open source Blender 3D modeling program,
more than that, I wanted to create object for 3D printing on millimeter scale.

My initial assumption were,
that it is all impossible and too hard, and I might as well program my own program.

I spent two days, just preparing for failure,
by the time I sat down to blender, I forgot all the key combinations.

I just remembers Shift + S,
which turned out not to be useful.

---

I sat down in-front of my commuter,
and it felt like all I have done thus far is put on a helmet in expectation for failure.

I remembers to right click on some numbers in the lower right corner to turn on statistics,
and this was useful when I was cloning objects, as I could see if the clone operation happened or not.

One time I pressed Control + S, it didn't work,
my own fault probably, but I like double checking things.

I remember that Blender has multiple modes,
the initial mode is object selection, and when you have a selected object, you can hit TAB to edit it.

But I still ended up clicking on the user interface,
there is a drop-down box that says Object Mode, and you can switch that to edit mode.

---

The first thing I searched the internet for, even before doing anything was:
"Blender, how to move by one millimeter".

And I discovered the craziest thing,
I've never seen anything like it.

Select part of the cube, with a mouse,
but then GO FULL KEYBOARD:

Press "G" to grab/move what you selected,
then press either X, Y, or Z, to pick the axis that you want to move the grabbed object on, and then enter the millimeters (once you setup Blender for milliliter scale)

It is crazy how amazing that is,
you can grab the 3 fundamental things, a point in 3d space, like the corner of a cube, an edge or a line that connects points, or a face like the side of a cube.

Grabbing an edge, will affect the face and the vertices, grabbing a face affects the lines and the vertices,
and grabbing a vertex (a point) will move the lines in that part of the 3D model and the face will change too.

---

So you hit W to go into select mode, and then 1, 2 or 3,
to pick selection mode, vertex, line, or face.

And then you have to pint or drag and select with the mouse,
the mouse is perfect for selecting little things.

Holding down the middle mouse button,
rotates a camera angle so you can look around the cube.

Once I did this couple of times,
grab a selected something, pick an axis, and move it on the unit scale, millimeters in my case.

Things got even easier,
they got insanely easier.

Because once you type in the number, an hit enter, and the object moves,
a little box pops up on the lower left, that not only tells you what you just did, but lets you change it.

When you specify how far you have to move something,
there is no input box, you are just typing at Blender, but here is a little input box, and you get to change or fix what you just did.

---

I almost jumped out of my chair,
because, I knew something else about 3D editing programs...

When you are clicking around on the screen,
select the move tool by clicking the pointy cross icon, that is like the universal icon for moving things in graphic programs....

You get these red, green, blue arrows,
that look like this annoying extra feature, that announces where the 3D X, Y, Z dimensions are.

But see, ages ago, when I was pointlessly clicking at some other program,
I discovered that these arrows are not telling you which way is X, Y, and Z.

They are not for informing you,
they are there to let you move the object that you just clicked on, but snapped to the axis that the arrow symbolizes.

This, combined with the box that pops up on the lower left,
that lets me tweak the operation that just occurred, gives me millimeter precision to all my designs.

I simply move a thing very crudely,
kind of ballpark just to get it in the right area, and then when the confirmation box pops up - my goodness - I set the precise value that I need.

---

In a snap,
I created a new wallet design.

I design wallets for 3D printing,
to learn the tool chain, and experiment with everything.

---

I was aware of a modifier menu, marked by a wrench icon,
that becomes available when a cube - for example - is selected.

---

I've noticed a modified named Boolean,
that is the same crazy name for the most useful feature in 3D editing that I just groked in FreeCAD.

I added a cylinder to my scene, to create holes for my elastic paracord that makes the wallets go, and copied it a bunch of times,
positioning everything very precisely and somewhat trying to imagine where the para-cord needs to be to joint two halves of a wallet.

Then I added super low resolution spheres,
which only have six sides in that state, and when intersecting a wallet under the Boolean modifier create a hexagonal hole.

And added an array modifier to the spheres, that immediately created multiple copies,
this means I could create a pretty wallet face, and break up the solid plastic back.

I threw the carefully positioned cylinders and the array of hexagonal spheres,
into its own scene collection.

And told the boolean modifier to use all the shapes in the collection - I've noticed that there was an option for that in a drop-down,
and selected the DIFFERENCE MODE, which combines the collection and my wallet in a substractive way.

This is something I figured out on my own,
by just looking at the different modifiers and options.

---

[And just like that, the mars wallet was born][1],
there is a sample on TinkerCAD, and can be viewed in 3D.

I did make an error, and I didn't make the cylinders big enough to make a hole for my para-cord,
I'll have to work on that.

When I was using cylinders,
I didn't know how to use the array feature yet, now I can position everything in a minute, not an hour.

---

If I had to do all this back in high school,
it would take a week, as I would have to play around with a few programs to get an idea how things work.

If I had a teacher standing over me,
telling me what not to do, or how to do things, or that it is time to go as other students need the computer, or threaten me with failing a class...

Or force me to prepare for a quiz where I has to uselessly explain the difference between face, edge and a vertex,
or the side of a cube, lines that make a side, point that tell the vertices where to go.

I would fail another class,
teachers are something else.

---

My advice, is to learn at home,
is to learn for real at out own pace, and the sequence that matches our existing knowledge first.

And learn things that are interesting to us,
that we are in context of - that we are into.

---

For example, get some cheap clip on lenses for your phone,
and start rebuilding all Indiana Jones Scenes to learn movie making.

Or setup an online store that sells 3D models, or get a 3D printer,
and then get into learning 3D modeling.

Get a Pico Projector, or an office projector,
and trace your friend's photos, on a large drawing board, before you start learning portraits.

Learn programming, and P%.js to create generative art,
and then start learning the flimsy language of mathematics, is you still want to.

Take a few lmms tutorials,
and begin composing your own music, it is only a matter of slowly moving around the scale, a nice kicker back beat in the bass line editor.

---

This is the real education,
creating things that we enjoy, that we are proud of, and that overtime make learning new things even easier.

We are all genius level smart, school grades and tests are fake,
it is just mostly a show to make money off of students, or make soundbites for re-election campaigns.

With knowledge comes wisdom,
and with wisdom comes greatness.

[1]: https://csg.tinkercad.com/things/iOcookFeG4o/t725.png?rev=1629508015603000000&s=&v=1

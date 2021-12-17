# drawio-statechart-lib
Statechart library for diagrams.net (draw.io)

# Online installation

You can install this library in the online diagrams.net (formerly known as draw.io) using the following link:

[Install this library on diagrams.net](https://app.diagrams.net/?splash=0&clibs=Uhttps%3A%2F%2Fraw.githubusercontent.com%2Fsamihult%2Fdrawio-statechart-lib%2Fmain%2FStatecharts.xml)

# Desktop installation

Download the file [Statecharts.xml](https://raw.githubusercontent.com/samihult/drawio-statechart-lib/main/Statecharts.xml) to a comfortable directory. Then, in the desktop application, choose from the "File" menu "Open library...".

# Examples

These diagrams are drawn using this library.

### Simple

This statechart models the behaviour of a simple door with no lock.

![Example – simple](./img/examples-simple.png)

### Orthogonal regions

This statechart models the behaviour of a two simple doors, left and right.

![Example – orthogonal](./img/examples-orthogonal.png)

### Nested state

This statechart models the behaviour of a simple door with a simple mechanical lock. 

![Example – nested](./img/examples-nested.png)

### Final state

This statechart is an FSM that corresponds to a regular expression `ab*c`.

![Example – final](./img/examples-final.png)

### Transient state

This statechart has a transient state. The dashed line is just a visual cue –
the (complementary) "always" transitions make it transient. 

![Example – transient](./img/examples-transient.png)


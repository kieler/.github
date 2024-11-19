# The KIELER Project

KIELER is a research project about enhancing the graphical model-based design of complex software systems.
It is developed by the [Real-Time and Embedded Systems group](http://www.rtsys.informatik.uni-kiel.de/) at [Kiel University](http://www.uni-kiel.de/).

The KIELER name was initially an acronym for _Kiel Integrated Environment for Layout Eclipse Rich Client_ but the project is no longer aimed at the [Eclipse platform](https://www.eclipse.org/ide/) specifically, as many projects under this umbrella are available as standalone tools, Java and JavaScript libraries, and [VS Code extensions](https://marketplace.visualstudio.com/publishers/kieler).
All KIELER projects have in common that they provide or utilize [pragmatics-aware modeling](https://rtsys.informatik.uni-kiel.de/~biblio/downloads/papers/isola22.pdf) concepts and technologies.
The pragmatics of model-based system design aims to improve comprehensibility of diagrams, improve development and maintenance time, and improve the analysis of dynamic behavior.

## Structure

* **Layout**\
Automatic graph layout is a key enabler for pragmatics-aware modeling, and therefore one of the major research topics.
The [ELK](https://github.com/eclipse/elk) layout framework is hosted under the Eclipse Foundation but is part of the KIELER initiative and actively developed by the KIELER team.
The [JavaScript port of ELK](https://github.com/kieler/elkjs), however, can be found here under the KIELER organization.

* **Diagrams**\
The idea of modeling pragmatics is closely linked to diagrams.
The [KLighD](https://github.com/kieler/KLighD) framework provides quick and lightweight diagram synthesis support, transient view management, and dynamic browsing.

* **Semantics**\
The [semantics](https://github.com/kieler/semantics) part of KIELER focuses on research in the area of modeling languages for embedded and safety-critical systems, especially synchronous languages, in combination with pragmatics-aware modeling techniques.
[Sequentially Constructive Charts (SCCharts)](https://github.com/kieler/semantics/wiki/home) are a synchronous state chart dialect with sequentially constructive semantics.
The KIELER tooling spans from editing to compilation, all using a model-based approach and on-the-fly visualization.

* **Risk analysis**\
Safety analyses are a crucial part of proving safe software systems.
The KIELER [PASTA](https://github.com/kieler/pasta) tool combines the Systems Theoretic Process Analysis (STPA) approach with pragmatics-aware modeling and visualization techniques.

* **Software project visualization**\
Pragmatics-aware visualizations can aid in understanding complex structures, such as large software systems.
KIELER's [SoftwareProjectViz](https://github.com/kieler/SoftwareProjectViz) is a visualization generator for arbitrary (software) projects, enabling the interactive exploration and documentation of project structures based on diagrams.


You can find further information and documentation for the different projects in the wikis of the respective repositories.

***

![kieler_logo](https://github.com/kieler/.github/assets/25612037/9d78fcc0-d901-4a43-a8f0-eb243aab2354)


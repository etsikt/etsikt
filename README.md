# Erlend Thune

This is my profile page for the work I do for the Norwegian directorate for education and training. 

I use [another profile](https://github.com/erlendthune) for my private projects. 

Below is a description of some of the projects I work on.

# Canvas LMS custom frontend

I maintain the GUI for [Norways largest e-learning portal](https://kompetanse.udir.no) 
in [this repository](https://github.com/matematikk-mooc/frontend). 

# LTI

To expand the functionality of the GUI above, I first made some initial prototypes of an LTI module through these projects:

- [KPAS-LTI](https://github.com/etsikt/KPAS-LTI)
- [KPAS](https://github.com/matematikk-mooc/KPAS)

These were later developed further into [kpas-api](https://github.com/matematikk-mooc/kpas-api) by external developers, and is now maintained by me.

# Interactive video transcripts

Inspired by the interactive video transcripts used in the [Coursera platform](https://www.coursera.org/), I made javascript code to do the same for
YouTube videos. I first mentioned the project [in the Canvas community](https://community.canvaslms.com/t5/Canvas-Developers-Group/Interactive-YouTube-transcript/m-p/159732) encouraging people to improve it. The code was later made as a separate module by 
[DMR-coding](https://github.com/DMR-coding), and I am proud to be [accredited for my work there.](https://github.com/DMR-coding/youtube-dynamic-transcripts#acknowledgements)

I've later developed the same functionality for Vimeo. That solution requires both backend and frontend code, and currently 
the backend code is only available 
in the KPAS-API described above, not as an independent module. An example of how the interactive vimeo transcripts work 
[can be seen here](https://www.erlendthune.com/vimeo/vimeo.html). Notice that you can click anywhere in the interactive transcript, to make
the video start playing from the corresponding timestamp.

# QTI converter
[QTI](https://www.imsglobal.org/question/index.html) is as standard for exchanging digital questions. I wrote a PHP script
to convert questions from excel to QTI, which can be [accessed here](https://www.erlendthune.com/xborrow/canvastabtoqti.php). 
I got a request from an employee of the [Americana university in Paraguay](https://www.americana.edu.py/) to reuse the code,
which I then [provided here](https://github.com/etsikt/canvastabtoqti).

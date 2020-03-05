---
title: "Distributed simplex algorithm"
excerpt: "An implementation of a distributed version of the well-known simplex algorithm<br/><img src='/images/Agent.png'>"
collection: projects
---

<a href="http://www.youtube.com/watch?feature=player_embedded&v=sib7pv8JoH4
" target="_blank"><img src="http://img.youtube.com/vi/sib7pv8JoH4/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>

**Introduction** 

An implementation of a distributed version of the well-known simplex algorithm, is given in this report.
The aim is to solve degenerate linear programs on asynchronous peer-to-peer networks with distributed information structures. 
So, a network of agents is considered, where every agent knows only a subset of information, and they run simplex algorithm by updating and sharing their base, until they will agree on a common solution. It is showed how the multi agent assignment problem can be efficiently solved by using a distributed structure, and it is provided simulations in the robot operating system environment.

**Based on the pubblication:**

```
@article{burger2012distributed,
  title={A distributed simplex algorithm for degenerate linear programs and multi-agent assignments},
  author={B{\"u}rger, Mathias and Notarstefano, Giuseppe and Bullo, Francesco and Allg{\"o}wer, Frank},
  journal={Automatica},
  volume={48},
  number={9},
  pages={2298--2304},
  year={2012},
  publisher={Elsevier}
}
```

**Report**

<object data="http://francovia.github.io/files/DCS.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="http://francovia.github.io/files/DCS.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="http://francovia.github.io/files/DCS.pdf">Download PDF</a>.</p>
    </embed>
</object>

**Repository**
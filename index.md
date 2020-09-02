## tuDHM
### Fast, automatic and accurate method 

tuDHM is an algorithm to recover the complex object information for a single-shot digital holographic microscope (DHM) operating in the telecentric regimen. The algoritm is based on the minimization of a cost function that finds the best numerical conjugated reference beam to compensate the filtered object information, eliminating any undesired phase perturbation due to the tilt between the reference and object waves. 

### Methods of use

We have develop two implementation, tuDHM for developers that allow to research work with direct with the .m files of matlab and a GUI version for people that not have knoledge about matlab.

### tuDHM developers
This version is addressed to developers or research with Matlab knowledge. The version contain seven function where the main function is called tuDHM.m


To work with `tuDHM.m` the user should read the hologram, and input the initial parameters [lambda, pixel sizes in both axis (x,y)]

### read the hologram
```markdown
 %% load hologram
 filename = 'name hologram.tif' # The hologram must be in the same folder when tuDMH is running
```

### input parameters
```markdown
  %% parameters of reconstruction (this parameters depend of the hologram record)  
  lambda = 0.633;% wavelength used to recorded the hologram
  dx = 6.9;% size of pixel size X
  dy = 6.9;% size of pixel size Y
```

### tDHM GUI
This version contains a GUI friendly that is focus for anyone that required obtain the numerica phase reconstruction of holograms without knowledge of Matlab platform. 

### Manual
[Dowload](https://drive.google.com/file/d/15XhSz9R1HQYQ7RUuUUGRnO17uYsaBXE5/view?usp=sharing)

### Downloads



### Funding

This project has received funding from the University of Memphis


### Credits

* tuDHM is developed in MATLAB. (2020). version 7.10.0 (R2020a). Natick, Massachusetts: The MathWorks Inc.


* For the unwrapping step, tuDHM implements the code developed by *M.A. Herraez et.al.* 


M. A. Herraez, D. R. Burton, M. J. Lalor, and M. A. Gdeisat, "Fast two-dimensional phase-unwrapping algorithm based on sorting by reliability following a noncontinuous path", Applied Optics, Vol. 41, Issue 35, pp. 7437-7444 (2002).  


M. F. Kasim, "Fast 2D phase unwrapping implementation in MATLAB" [unwrapping](https://github.com/mfkasim91/unwrap_phase/).  

### Citation
If using tuDHM for publication, please kindly cite the following: R. Castaneda and A. Doblas, "Fast and automatic algorithm to universal recovery of the quantitative phase distribution in digital holographic microscopy," IEEE

### Support or Contact

* Raul Castaneda 


email: (*rcstdq@memphis.edu*)


Google Scholar:[Raul Castaneda](https://scholar.google.es/citations?user=PvvDEMYAAAAJ&hl=en)


ResearchGate: [Raul Castaneda](https://www.researchgate.net/profile/Raul_Castaneda_Quintero)


* Ana Doblas 


email: (*<adoblas@memphis.edu*)


Google Scholar: [Ana doblas](https://scholar.google.es/citations?user=PvvDEMYAAAAJ&hl=en)


ResearchGate: [Ana Doblas](https://www.researchgate.net/profile/Ana_Doblas2)


The main research of the tuDHM project is Ana Doblas 


You can use the [editor on GitHub](https://github.com/OIRL/tuDHM/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.






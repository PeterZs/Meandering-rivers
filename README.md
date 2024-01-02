# Meandering-rivers
Source code for the paper "Authoring and Simulating Meandering Rivers", published at Transactions on Graphics and presented at Siggraph Asia 2023. This is aimed at researchers, students or profesionnals who may want to reproduce **some** of the results described in the paper.

[Project Page](https://aparis69.github.io/public_html/projects/paris2023_Meanders.html).

[Paper](https://hal.science/hal-04227965)

### Important notes
* This code is **not** the one which produced the scenes seen in the paper. Everything has been *recoded* on my side to make sure it is free to use. The original code from the paper is dependent on internal libraries that cannot be shared.
Hence, the results as well as the timings may differ from the ones in the paper.
* This is **research** code provided without any warranty. However, if you have any problem you can still send me an email or create an issue.

### Testing
There is no dependency. Running the program will output several PPM files that can visualized using an image viewer. Tests have been made on:
* Visual Studio 2022: double click on the solution in ./VS2022/ and Ctrl + F5 to run

In you can't compile or run the code, some results are available in the Results/ folder in the repo (everything in there was generated by this code).

### Citation
If you use this code in any way, please credit the original article:
```
@article{Paris2023Meanders,
  author = {Paris, Axel and Gu{\'e}rin, Eric and Collon, Pauline and Galin, Eric},
  title = {Authoring and simulating meandering rivers},
  journal = {ACM Transactions on Graphics (Proceedings of Siggraph Asia 2023)},
  volume = {42},
  number = {6},
  year = {2023},
  pages = {1--14}
}
```	

### Additional notes
There are great resources on the web on the topic that did not make it into the final paper but still deserve to be mentioned. Here is a non-exhaustive list:
* [Meander - Robert Hodgin](https://roberthodgin.com/project/meander): a procedural system for generating historical maps of rivers that never existed. Insanely good visualization, and describe the core components of the migration in a very accessible manner. Go take a look!
* [Procedural Hydrology, Nicholas McDonald](https://nickmcd.me/2023/12/12/meandering-rivers-in-particle-based-hydraulic-erosion-simulations/#meandering-river-simulation): on top of [his first blog post](https://nickmcd.me/2020/04/15/procedural-hydrology/) on erosion simulation, this second one that came out in December allows to reproduce very convincing meandering rivers over an entire terrain using a particle-based system. I did not look into the (very) detailed blog post that describe the method yet, but the visuals are great.
* [Meandering River - code exploration & simulation, onformative](https://vimeo.com/107158489): cool video showing some simulation of meandering rivers. Mesmerizing as always!


### Missing
There are still some things missing from the original paper. A full list of what is missing will added here in the future.

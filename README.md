# Diagram Evaluation Dataset 

This repo contains a dataset of AI-generated diagrams evaluated for hallucination,
logical organization, connectivity, and layout aesthetic. Each file name contains the ID of the corresponding text source, the method it was generated with and the model. 

For example, the diagram below was generated from the text ID 7 with the zero-shot generation and the o3 model.
```text
diagram_[7]refined_0SHOTo3.png
```

The diagrams are licensed under CC-BY-4.0 with an exception for the diagrams (ID 25) based on the text by Olivier Bonaventure. 2011. Computer Networking : Principles, Protocols and Practice https://github.com/obonaventure/cnp3/ licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/ 

[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

## Dataset Use
If you use the dataset, cite it as [Logacheva, Evanfiya, et al. "In-Context Learning for Diagram Code Generation: What is the Effect on Hallucination and Quality?"][arxiv]

[arxiv]: https://arxiv.org/abs/2601.20476.
```
@misc{logacheva2026,
      title={In-Context Learning for Diagram Code Generation: What is the Effect on Hallucination and Quality?}, 
      author={Evanfiya Logacheva and Arto Hellas and Tsvetomila Mihaylova and Juha Sorva and Ava Heinonen and Juho Leinonen},
      year={2026},
      eprint={2601.20476},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2601.20476}, 
}
```
The evaluations are in
```text
expert_eval/evaluation.csv
expert_eval/evaluation_data_raters.csv
```

The diagrams are in 
```text
generated_content/
```

## Sources
The source texts, their ID, and their modified versions used in the diagrams are place in 

```text
texts.csv
```

The texts used for the diagrams are under CC BY 4.0 https://creativecommons.org/licenses/by/4.0/ unless stated otherwise. 
1.	Arto Hellas. 2025. Web software development [online course materials]. https://fitech101.aalto.fi/en/courses/web-software-development 
2.	Jukka Suomela. 2025. Programming Parallel Computers https://ppc.cs.aalto.fi/
3.	Arto Hellas. 2025. Web software development [online course materials]. https://fitech101.aalto.fi/en/courses/web-software-development
4.	Arto Hellas. 2025. Web software development [online course materials]. https://fitech101.aalto.fi/en/courses/web-software-development
5.	Belinda Weaver. 2025. Introducing Computational Thinking https://librarycarpentry.github.io/lc-computational-thinking/aio.html
6.	Belinda Weaver. 2025. Introducing Computational Thinking https://librarycarpentry.github.io/lc-computational-thinking/aio.html
7.	James Allen, Markus J. Ankenbrand, James Baker, Sean Barberie, Christian Calogero Barra, Trevor Bekolay, John Blischak, K. Azalee Bostroem, Andrew P Boughton, Geoffrey Boushey, Hugo Bowne-Anderson, Petrina Collingwood, Logan Cox, Matt Critchlow, Tim Dennis, Jonah Duckles, Shyam Dwaraknath, Jason Ellis, Rémi Emonet, … yremmits. (2024). LibraryCarpentry/lc-python-intro: Python Intro for Libraries 2024-06 Update (2024.06). https://librarycarpentry.github.io/lc-python-intro/
8.	Naupaka Zimmerman and Sehrish Kanwal and Matthieu Bruneaux and Craig Gross. R for Reproducible Scientific Analysis, 2025 https://swcarpentry.github.io/r-novice-gapminder/07-control-flow.html
9.	Thomas Cason and Rohit Goswami and Hugo Gruson and Katie O'Mahony. Programming with R, 2025 https://swcarpentry.github.io/r-novice-inflammation/04-cond.html
10.	Juho Hirvonen and Jukka Suomela. 2025.Distributed Algorithms https://jukkasuomela.fi/da2020/da2020-06.pdf
11.	Juho Hirvonen and Jukka Suomela. 2025.Distributed Algorithms https://jukkasuomela.fi/da2020/da2020-06.pdf
12.	Benson Muite Pariksheet Nanda Amanda Kis. 2025. The Unix Shell: Summary and Setup https://swcarpentry.github.io/shell-novice/
13.	Gerard Capes. 2025. Automation and Make: Summary and Setup https://swcarpentry.github.io/make-novice/
14.	Arto Hellas. 2025. Web software development [online course materials]. https://fitech101.aalto.fi/en/courses/web-software-development
15.	Naupaka Zimmerman and Sehrish Kanwal and Matthieu Bruneaux and Craig Gross. R for Reproducible Scientific Analysis, 2025 https://swcarpentry.github.io/r-novice-gapminder/04-data-structures-part1.html
16.	Arto Hellas. 2025. Web software development [online course materials]. https://fitech101.aalto.fi/en/courses/web-software-development
17.	Arto Hellas. 2025. Web software development [online course materials]. https://fitech101.aalto.fi/en/courses/web-software-development
18.	Arto Hellas. 2025. Web software development [online course materials]. https://fitech101.aalto.fi/en/courses/web-software-development
19.	Thomas Cason and Rohit Goswami and Hugo Gruson and Katie O'Mahony. Programming with R, 2025 https://swcarpentry.github.io/r-novice-inflammation/04-cond.html
20.	Juho Hirvonen and Jukka Suomela. 2025.Distributed Algorithms https://jukkasuomela.fi/da2020/da2020-06.pdf
21.	Martin Frické. 2024. Artificial Intelligence and Librarianship: Notes for Teaching (3rd ed.) https://softoption.us/AIandLibrarianship
22.	Stephen Davies. 2020. The Crystal Ball Instruction Manual - version 1.1 Volume One: Introduction to Data Science https://github.com/divilian/crystal-ball-1
23.	Stephen Davies. 2020. The Crystal Ball Instruction Manual - version 1.1 Volume One: Introduction to Data Science https://github.com/divilian/crystal-ball-1
24.	Paul W. Bible and Lucas Moser. 2023. An Open Guide to Data Structures and Algorithms https://pressbooks.palni.org/anopenguidetodatastructuresandalgorithms/
25.	Olivier Bonaventure. 2011. Computer Networking : Principles, Protocols and Practice https://github.com/obonaventure/cnp3/ This work is licensed under the Creative Commons Attribution-ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/3.0/ or send a letter to Creative Commons, 444 Castro Street, Suite 900, Mountain View, California, 94041, USA. 
	
	

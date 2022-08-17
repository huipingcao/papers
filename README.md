# papers
This repository maintains a list of papers that our lab looks into. 

## [Content](#content)

<table>
<tr><td colspan="2">1. Hoang Le's work are <a href="https://github.com/lehgtrung/paper-reading-list">here</a> </td></tr>
<tr><td colspan="2">2. Huiying's work are <a href="https://github.com/huipingcao/papers/tree/main/Huiying">here</a> </td></tr>
<tr><td colspan="2">3. Jiefei Liu's work are <a href="https://github.com/huipingcao/papers/tree/main/Jiefei">here</a></td></tr>
<tr><td colspan="2">4. Erick's work are <a href="https://github.com/ecdraayer/Paper_List">here</a></td></tr>
<tr><td colspan="2">5. Selective papers marked by Huiping <a href="cao_list.md">here</a></td></tr>
<tr><td colspan="2"><a href="#Physics-guided-NN-models">6. Physics guided NN models</a></td></tr>

</table>


## [Physics guided NN models](#content)
1. **Physics-Guided Machine Learning for Scientific Discovery: An Application in Simulating Lake Temperature Profiles.** Machine Learning (cs.LG), 2020. [paper](https://arxiv.org/abs/2001.11086)

   *Xiaowei Jia, Jared Willard, Anuj Karpatne, Jordan S Read, Jacob A Zwart, Michael Steinbach, Vipin Kumar*

1. **Physics Guided RNNs for Modeling Dynamical Systems: A Case Study in Simulating Lake Temperature Profiles.** Computational Physics (physics.comp-ph), 2019. [paper](https://arxiv.org/abs/1810.13075)

   *Xiaowei Jia, Jared Willard, Anuj Karpatne, Jordan Read, Jacob Zwart, Michael Steinbach, Vipin Kumar*
   
1. **Label-Free Supervision of Neural Networks with Physics and Domain Knowledge.** AAAI, 2017. [paper](https://www.aaai.org/Conferences/AAAI/2017/PreliminaryPapers/12-Stewart-14967.pdf)

   *Russell Stewart, Stefano Ermon*
   
## Steps to set up the Kaiju environment

### Trung's set up on Kaiju
1. Install Anaconda
If you haven't installed Anaconda in your home directory (~/<your_cs_username>) yet, then do this
> rm -f ~/anaconda3

> # Create anaconda folder in backup space 
> mkdir /home/student_no_backup/thoang/anaconda3

> # Link to temporary storage
> ln -s /home/student_no_backup/thoang ~/anaconda3
These commands create a symlink between your anaconda in your home directory to anaconda in your work directory because your home directory's capacity is not big enough to store the anaconda.
In case you did install Anaconeda in your home directory (~/<your_cs_username>), do this
> # Remove the directory from the temporary storage area
> rm -rf /home/student_no_backup/thoang/anaconda3

> # Move your current anaconda3 to temporary storage
> mv ~/anaconda3 /home/student_no_backup/thoang/

> # Link to temporary storage
> ln -s /home/student_no_backup/thoang/anaconda3 ~/anaconda3

After that you can install Anaconda by following these steps: https://kengchichang.com/post/conda-linux/

2. After installing Anaconda 
You can put your working projects inside this directory: /home/student_no_backup/<your_cs_username> and create a new conda environment for each project. Enviroments can be used accross servers (Kaiju, Shamir,...)



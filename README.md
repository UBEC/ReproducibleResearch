# Coding for Reproducible Research
Workshop on code compatible with Reproducible Research using Jupyter notebooks

## Resources that are used in this class
* https://github.com/UBEC/ReproducibleResearch/
* https://reproducible-science-curriculum.github.io/rr-jupyter-workshop/
    * https://github.com/Reproducible-Science-Curriculum
* https://github.com/sara-nl/jupyter-bigdata-notebooks

## Example of a notebook we use in teaching bioinformatics
* https://github.com/UMCUGenetics/BachelorBfx

---

## The outline for today:
1. Get code ready in your environment
    * https://github.com/UBEC/ReproducibleResearch/blob/master/Prepping_RS_Workshop.ipynb

2. Go through Data carpentry intro
    * introduction-RR-Jupyter/notebooks/Intro-to-reproducible-research.ipynb
    * introduction-RR-Jupyter/notebooks/Jupyter_Intro_Background.ipynb

3. A versioned jupyter notebook
    * fork https://github.com/UBEC/ReproducibleResearch
    * clone **your own version** of ReproducibleResearch
    * open **VersionedNotebook** through jupyter interface
    * edit the code to perform the desired analysis on the Human IDs
    * commit the code to the repository with a tag
    * run analysis again with different settings for **Mouse**
    * [origin=False]
    * commit the code to the repository with a **different** tag
    * check out the versions on github
    * https://github.com/UBEC/ReproducibleResearch/compare/v2.0...v3.1

**GIT code example**
~~~ bash
! git commit -a -m "ID version"
! git tag -a v1.4 -m "ID version"
! git push origin v1.4
~~~

4. **bio-break**

5. See some SPARK in action
    * jupyter-bigdata-notebooks/notebooks/02-spark-intro.ipynb
    * jupyter-bigdata-notebooks/notebooks/03-spark-dataframes.ipynb

---

## Tips & Tricks
* https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/

**Use Git aware text-editors for libraries/readmes etc**
* https://help.github.com/articles/associating-text-editors-with-git/
    * https://atom.io/

**Do not put everything under git control:**
~~~ bash
echo ".ipynb_checkpoints" >> .gitignore
~~~
* https://gist.github.com/pbugnion/ea2797393033b54674af
* http://stackoverflow.com/questions/18734739/using-ipython-notebooks-under-version-control

**Plotting, embedding, etc...**
* https://blog.dominodatalab.com/lesser-known-ways-of-using-notebooks/
* https://plot.ly/python/ipython-notebook-tutorial/

---

## Further reading
* https://ropensci.github.io/reproducibility-guide/
* https://git-scm.com/book/en/v2/
    * https://git-scm.com/book/en/v2/Git-Basics-Tagging
* https://github.com/jupyter/notebook
* https://github.com/tanghaibao/goatools

## More on getting started
* https://github.com/Reproducible-Science-Curriculum/introduction-RR-Jupyter/blob/master/notebooks/getting_started_with_jupyter_notebooks.ipynb

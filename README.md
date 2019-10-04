# Data-Mining-Techniques-Project

<h2>Problem Definition</h2>
<p>This Group Project was implemented as part of the course: Data Mining Techniques offered by the M.Sc in Data Science of the Department of Informatics, School of Sciences, National and Kapodistrian University of Athens.</p>
<p>The problems that this repository is called to solve are:
<ul>
  <li>The classification of different articles in their respective categories</li>
  <li>Duplicates detection</li>
  <li>Wordcloud creation for each category</li>
</ul>
</p>

<h2>Dataset</h2>
<p>The dataset that is used can be found in train_set.zip. It contains 12265 articles, both title and content and also the category in which each one belongs.</p>

<h2>Processing & Classifiers</h2>
<p>In order to apply the classifiers (SVM and Random Forest) the articles were vectorized by using in each time one of the Tf-Idf-Vectorizer, the Single Value Decomposition or the Average Word Vector (Word2Vector). The stop-words were removed and the Snowball Stemmer was applied. Each classifier was used on each vectorization.</p>

---
layout: default
title: Creating Parse Trees
---
# Creating Parse Trees

---

In this exercise, I was asked to create constituency-based parse trees for three sentences: “The government raised interest rates,” “The internet gives everyone a voice,” and “The man saw the dog with the telescope.” I constructed the trees using standard syntactic categories such as NP (noun phrase), VP (verb phrase), and PP (prepositional phrase). The final example illustrated structural ambiguity, as the prepositional phrase “with the telescope” can modify either the verb (saw with the telescope) or the noun (the dog with the telescope). The resulting trees were generated and visualised in Python using NLTK and Matplotlib.


Full version available <a href="pdf/ParseTrees.pdf" target="_blank" rel="noopener noreferrer">here</a>



<style>
  .back-button {
    display: inline-block;
    background-color: white;
    color: #006699;
    text-decoration: none;
    padding: 5px 10px; /* Reduced padding for a smaller button */
    font-size: 12px; /* Smaller font size */
    border: 1px solid #006699; /* Thinner border */
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s, color 0.3s;
    margin: 15px 0; /* Adds space above and below the button */
  }
  .back-button:hover {
    background-color: #006699;
    color: white;
 }
</style>

<div class="button-container">
   <a href="https://dzervenes.github.io/intelligent-agents/" class="back-button">Back</a>
</div>

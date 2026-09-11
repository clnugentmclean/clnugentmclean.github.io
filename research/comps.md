---
title: "Comps"
layout: single
permalink: /research/comps/
---
<input type="text" id="ref-search" placeholder="Search by author or title..." style="width:100%; padding:0.6em; margin-bottom:1em; font-size:1em; border:1px solid #ccc; border-radius:4px;">

To search through the citations for *"Mussulman Fanatics": A Computational Analysis of Anti-Muslim Racism in The Times from the 1857 Sepoy Rebellion to the Rushdie Affair*, use the text box above to search the primary and secondary sources. Use the drop down arrows to expand and collaspe the list of primary and secondary sources. The search box will display sources that match the search in the expanded drop down menus.

<details open>
<summary><strong>Primary Sources</strong> (click to collapse)</summary>
<ul id="primary-list">
<li>Ahmad, Rafiuddin. “The Battle of Omdurman and the Mussulman World.” <em>Nineteenth Century</em> 44, nos. 688–696 (1898).</li>


</ul>
</details>


<details>
<summary><strong>Secondary Sources</strong> (click to expand)</summary>

<ul id="secondary-list">
<li>Abbas, Sadia. <em>At Freedom’s Limit: Islam and the Postcolonial Predicament</em>. Fordham University Press, 2014.</li>


</ul>

</details>

<script>
document.getElementById('ref-search').addEventListener('input', function() {
  var query = this.value.toLowerCase();
  document.querySelectorAll('#primary-list li, #secondary-list li').forEach(function(item) {
    item.style.display = item.textContent.toLowerCase().includes(query) ? '' : 'none';
  });
});
</script>
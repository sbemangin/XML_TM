# ERREUR DANS LES DOSSIERS DU FICHIER  
unknown/COMMUN est vide TBNodeId:39861
## SF-36 
Liste des visites avec cette fiches :Quality of Life 

### QLQHEAD 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> QLQYN </b></td> 
 <td style='width:600px; text-align:left;'> Questionnaire rempli par le patient</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Yes</b> <br>🔘 0 - <b>No</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> QLQDT </b></td> 
 <td style='width:600px; text-align:left;'> Date de remplissage du questionnaire par le patient</td>
 <td style='width:600px; text-align:left;'>  <details> <summary>1 EditCheck </summary><table><tr><td> 5:[QLQHEAD.*][QLQDT]</td> </tr><tr> <td> <pre><code class='javascript'>#Action Expression 
[QLQHEAD][QLQYN] == '1'; 
#data Expression 
 
</code></pre> </td><td> This item is required.</td> </tr></table></details> </td>
 <td style='width:300px; text-align:center;'> 📅 DD/MM/YYYY  </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> QLQNO_R </b></td> 
 <td style='width:600px; text-align:left;'> Raison de non remplissage du questionnaire</td>
 <td style='width:600px; text-align:left;'>  <details> <summary>1 EditCheck </summary><table><tr><td> 5:[QLQHEAD.*][QLQNO_R]</td> </tr><tr> <td> <pre><code class='javascript'>#Action Expression 
[QLQHEAD][QLQYN] == '0'; 
#data Expression 
 
</code></pre> </td><td> This item is required.</td> </tr></table></details> </td>
 <td style='width:300px; text-align:center;'> Char - 50 </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> QLQEXPDT </b></td> 
 <td style='width:600px; text-align:left;'> Date à laquelle le questionnaire aurait dû être rempli</td>
 <td style='width:600px; text-align:left;'>  <details> <summary>1 EditCheck </summary><table><tr><td> 5:[QLQHEAD.*][QLQEXPDT]</td> </tr><tr> <td> <pre><code class='javascript'>#Action Expression 
[QLQHEAD][QLQYN] == '0'; 
#data Expression 
 
</code></pre> </td><td> This item is required.</td> </tr></table></details> </td>
 <td style='width:300px; text-align:center;'> 📅 DD/MM/YYYY  </td> 
 </tr>
</table>

### SF36G1 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFGH1 </b></td> 
 <td style='width:600px; text-align:left;'> 1. Dans l'ensemble, pensez-vous que votre santé est :</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Excellente</b> <br>🔘 2 - <b>Très bonne</b> <br>🔘 3 - <b>Bonne</b> <br>🔘 4 - <b>Médiocre</b> <br>🔘 5 - <b>Mauvaise</b> <br> </td> 
 </tr>
</table>

### SF36G2 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFHT </b></td> 
 <td style='width:600px; text-align:left;'> 2. Par rapport au même jour de la semaine dernière, comment trouvez-vous votre état de santé en ce moment ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Bien meilleur que la semaine dernière</b> <br>🔘 2 - <b>Plutôt meilleur</b> <br>🔘 3 - <b>À peu près pareil</b> <br>🔘 4 - <b>Plutôt moins bon</b> <br>🔘 5 - <b>Beaucoup moins bon</b> <br> </td> 
 </tr>
</table>

### SF36G3 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP1 </b></td> 
 <td style='width:600px; text-align:left;'> a. Efforts physiques importants tels que courir, soulever un objet lourd, faire du sport</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP2 </b></td> 
 <td style='width:600px; text-align:left;'> b. Efforts physiques modérés tels que déplacer une table, passer l'aspirateur, jouer aux boules</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP3 </b></td> 
 <td style='width:600px; text-align:left;'> c. Soulever et porter les courses</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP4 </b></td> 
 <td style='width:600px; text-align:left;'> d. Monter plusieurs étages par l'escalier</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP5 </b></td> 
 <td style='width:600px; text-align:left;'> e. Monter un étage par l'escalier</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP6 </b></td> 
 <td style='width:600px; text-align:left;'> f. Se pencher en avant, se mettre à genoux, s'accroupir</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP7 </b></td> 
 <td style='width:600px; text-align:left;'> g. Marcher plus d'un km à pied</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP8 </b></td> 
 <td style='width:600px; text-align:left;'> h. Marcher plusieurs centaines de mètres</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP9 </b></td> 
 <td style='width:600px; text-align:left;'> i. Marcher une centaine de mètres</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFP10 </b></td> 
 <td style='width:600px; text-align:left;'> j. Prendre un bain, une douche ou s'habiller</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Oui, beaucoup limité(e)</b> <br>🔘 2 - <b>Oui, un peu limité(e)</b> <br>🔘 3 - <b>Non, pas du tout limité(e)</b> <br> </td> 
 </tr>
</table>

### SF36G4 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFR1 </b></td> 
 <td style='width:600px; text-align:left;'> a. Avez-vous réduit le temps passé à votre travail ou à vos activités habituelles ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Quelques fois</b> <br>🔘 4 - <b>Rarement</b> <br>🔘 5 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFRP2 </b></td> 
 <td style='width:600px; text-align:left;'> b. Avez-vous accompli moins de choses que vous auriez souhaité ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Quelques fois</b> <br>🔘 4 - <b>Rarement</b> <br>🔘 5 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFRP3 </b></td> 
 <td style='width:600px; text-align:left;'> c. Avez-vous dû arrêter de faire certaines choses ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Quelques fois</b> <br>🔘 4 - <b>Rarement</b> <br>🔘 5 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFRP4 </b></td> 
 <td style='width:600px; text-align:left;'> d. Avez-vous eu des difficultés à faire votre travail ou toute autre activité ? (par exemple, cela vous a demandé un effort supplémentaire)</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Quelques fois</b> <br>🔘 4 - <b>Rarement</b> <br>🔘 5 - <b>Jamais</b> <br> </td> 
 </tr>
</table>

### SF36G5 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFRE1 </b></td> 
 <td style='width:600px; text-align:left;'> a. Avez-vous réduit le temps passé à votre travail ou à vos activités habituelles ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Quelques fois</b> <br>🔘 4 - <b>Rarement</b> <br>🔘 5 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFRE2 </b></td> 
 <td style='width:600px; text-align:left;'> b. Avez-vous accompli moins de choses que vous auriez souhaité ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Quelques fois</b> <br>🔘 4 - <b>Rarement</b> <br>🔘 5 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFRE3 </b></td> 
 <td style='width:600px; text-align:left;'> c. Avez-vous eu des difficultés à faire ce que vous aviez à faire avec autant de soin et d'attention que d'habitude ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Quelques fois</b> <br>🔘 4 - <b>Rarement</b> <br>🔘 5 - <b>Jamais</b> <br> </td> 
 </tr>
</table>

### SF36G6 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFSF1 </b></td> 
 <td style='width:600px; text-align:left;'> 6. Au cours de cette dernière semaine dans quelle mesure votre état de santé, physique ou émotionnel, vous a-t-il gêné(e) dans votre vie sociale et vos relations avec les autres, votre famille, vos amis, vos connaissances</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Pas du tout</b> <br>🔘 2 - <b>Un petit peu</b> <br>🔘 3 - <b>Moyennement</b> <br>🔘 4 - <b>Beaucoup</b> <br>🔘 5 - <b>Enormément</b> <br> </td> 
 </tr>
</table>

### SF36G7 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFBP1 </b></td> 
 <td style='width:600px; text-align:left;'> 7. Au cours de cette dernière semaine, quelle a été l'intensité de vos douleurs physiques ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Nulle</b> <br>🔘 2 - <b>Très faible</b> <br>🔘 3 - <b>Faible</b> <br>🔘 4 - <b>Moyenne</b> <br>🔘 5 - <b>Grande</b> <br>🔘 6 - <b>Très grande</b> <br> </td> 
 </tr>
</table>

### SF36G8 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFBP2 </b></td> 
 <td style='width:600px; text-align:left;'> 8. Au cours de cette dernière semaine, dans quelle mesure vos douleurs physiques vous ont-elles limité(e) dans votre travail ou vos activités domestiques ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Pas du tout</b> <br>🔘 2 - <b>Un petit peu</b> <br>🔘 3 - <b>Moyennement</b> <br>🔘 4 - <b>Beaucoup</b> <br>🔘 5 - <b>Enormément</b> <br> </td> 
 </tr>
</table>

### SF36G9 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFVT1 </b></td> 
 <td style='width:600px; text-align:left;'> a. vous vous êtes senti(e) dynamique ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFMH1 </b></td> 
 <td style='width:600px; text-align:left;'> b. vous vous êtes senti(e) très nerveux(se) ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFMH2 </b></td> 
 <td style='width:600px; text-align:left;'> c. vous vous êtes senti(e) si découragé(e) que rien ne pouvait vous remonter le moral ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFMH3 </b></td> 
 <td style='width:600px; text-align:left;'> d. vous vous êtes senti(e) calme et détendu(e) ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFVT2 </b></td> 
 <td style='width:600px; text-align:left;'> e. vous vous êtes senti(e) débordant(e) d'énergie ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFMH4 </b></td> 
 <td style='width:600px; text-align:left;'> f. vous vous êtes senti(e) triste et abattu(e) ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFVT3 </b></td> 
 <td style='width:600px; text-align:left;'> g. vous vous êtes senti(e) épuisé(e) ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFMH5 </b></td> 
 <td style='width:600px; text-align:left;'> h. vous vous êtes senti(e) heureux(se) ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFVT4 </b></td> 
 <td style='width:600px; text-align:left;'> i. vous vous êtes senti(e) fatigué(e) ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Très souvent</b> <br>🔘 3 - <b>Souvent</b> <br>🔘 4 - <b>Quelques fois</b> <br>🔘 5 - <b>Rarement</b> <br>🔘 6 - <b>Jamais</b> <br> </td> 
 </tr>
</table>

### SF36G10 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFSF2 </b></td> 
 <td style='width:600px; text-align:left;'> 10. Au cours de cette dernière semaine, y a-t-il eu des moments où votre état de santé, physique ou émotionnel, vous a gêné(e) dans votre vie et vos relations avec les autres, votre famille, vos amis, vos connaissances ?</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>En permanence</b> <br>🔘 2 - <b>Une bonne partie du temps</b> <br>🔘 3 - <b>De temps en temps</b> <br>🔘 4 - <b>Rarement</b> <br>🔘 5 - <b>Jamais</b> <br> </td> 
 </tr>
</table>

### SF36G11 

<table style='width:100%;'>
<tr>
<th style='width:50px; text-align:center;'><strong>Sas</strong></th>
<th style='width:600px; text-align:center;'><strong>Label de la question </strong></th>
<th style='width:300px; text-align:center;'><strong>Check</strong></th>
<th style='width:300px; text-align:center;'><strongRéponses possibles</strong></th>
</tr>
<tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFGH2 </b></td> 
 <td style='width:600px; text-align:left;'> a. Je tombe malade plus facilement que les autres</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Totalement vraie</b> <br>🔘 2 - <b>Plutôt vraie</b> <br>🔘 3 - <b>Je ne sais pas</b> <br>🔘 4 - <b>Plutôt fausse</b> <br>🔘 5 - <b>Totalement fausse</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFGH3 </b></td> 
 <td style='width:600px; text-align:left;'> b. Je me porte aussi bien que n'importe qui</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Totalement vraie</b> <br>🔘 2 - <b>Plutôt vraie</b> <br>🔘 3 - <b>Je ne sais pas</b> <br>🔘 4 - <b>Plutôt fausse</b> <br>🔘 5 - <b>Totalement fausse</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFGH4 </b></td> 
 <td style='width:600px; text-align:left;'> c. Je m'attends à ce que ma santé se dégrade</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Totalement vraie</b> <br>🔘 2 - <b>Plutôt vraie</b> <br>🔘 3 - <b>Je ne sais pas</b> <br>🔘 4 - <b>Plutôt fausse</b> <br>🔘 5 - <b>Totalement fausse</b> <br> </td> 
 </tr>
 <tr> 
<td style='width:50px; text-align:center; color:red; font-size: 10px;'> <b> Q0SFGH5 </b></td> 
 <td style='width:600px; text-align:left;'> d. Je suis en excellente santé</td>
 <td style='width:600px; text-align:left;'>   </td>
 <td style='width:300px; text-align:center;'> 🔘 1 - <b>Totalement vraie</b> <br>🔘 2 - <b>Plutôt vraie</b> <br>🔘 3 - <b>Je ne sais pas</b> <br>🔘 4 - <b>Plutôt fausse</b> <br>🔘 5 - <b>Totalement fausse</b> <br> </td> 
 </tr>
</table>

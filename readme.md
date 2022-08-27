Client chat (messagerie privée) ajax et php-------------------------------------------
Url     : http://codes-sources.commentcamarche.net/source/47177-client-chat-messagerie-privee-ajax-et-phpAuteur  : cs_zniko07Date    : 02/08/2013
Licence :
=========

Ce document intitulé « Client chat (messagerie privée) ajax et php » issu de CommentCaMarche
(codes-sources.commentcamarche.net) est mis à disposition sous les termes de
la licence Creative Commons. Vous pouvez copier, modifier des copies de cette
source, dans les conditions fixées par la licence, tant que cette note
apparaît clairement.

Description :
=============

il s'agit d'un client chat en ajax et php. Ce syst&eacute;me de messagerie g&eac
ute;re l'envoi de messages priv&eacute;s. 
<br />et marche avec des fichiers xm
l's donc pas besoin de base de donn&eacute;es et &ccedil;a devrait bien marcher 
m&ecirc;me sur des petits h&eacute;bergements.
<br /><a name='source-exemple'><
/a><h2> Source / Exemple : </h2>
<br /><pre class='code' data-mode='basic'>
j
'ai mis un exemple d'intégration dans le zip : client_nico.html
c'est trés simp
le a utiliser on initialise la session en faisant:
startSession(&quot;nom_d_uti
lisateur&quot;);

et pour faire un lien permettant d'inviter un membre a rejoi
ndre la conversation il suffit de faire:
&lt;a rel=&quot;chat&quot; name=&quot;
nom_d_utilisateur&quot;&gt;invite nom_d_utilisateur!&lt;/a&gt;

ensuite le des
ign est entiérement personalisable en css (la feuille de style dans le répertoir
e css....logique!)

voila ! a part ça j'ai mis un .htaccess pour a la racine p
arce que pour que ça marche il faut php5.

sinon j'ai un peu commenté le code,
 j'espére que ce sera assez lisible.
</pre>
<br /><a name='conclusion'></a><h2
> Conclusion : </h2>
<br />J'esp&eacute;re que &ccedil;a pourra servir &agrave
; quelqu'un.
<br />Comme c'est beaucoup plus amusant de programmer que d'&eacut
e;crire une documentation __ la source n'est pas document&eacute;e plus que ces 
explications, mais je pense que c'est quand m&ecirc;me assez utilisable comme &c
cedil;a, alors je la met en d&eacute;butant!
<br />Si vous utilisez cette sourc
e sur un projet &ccedil;a serait sympa de me montrer le r&eacute;sultat : nico@k
-wi.com
<br />Et sinon chattez bien!

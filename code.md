---
layout: page
title: Code
permalink: /code/
---
<div class="home">

<h1 class="page-heading">Wasserstein Dictionary learning and Wasserstein NMF</h1>
<p>
Relevant paper: Antoine Rolet, Marco Cuturi and Gabriel Peyré. <a href="{{ site.baseurl }}/res/pdf/Wasserstein_dictionary_learning.pdf">Fast Dictionary Learning with a Smoothed Wasserstein Loss.</a>. To appear in Proceedings of the 19th International Conference on Artificial Intelligence and Statistics (AISTATS) 2016, Cadiz, Spain. JMLR: W&CP volume 41. <a href="{{ site.baseurl }}/res/pdf/Supplementary_Wasserstein_dictionary_learning.pdf">Supplementary materials.</a>
</p>
<p>
Code available on the Github repository: <a href="http://arolet.github.io/wasserstein-dictionary-learning">http://arolet.github.io/wasserstein-dictionary-learning</a>
</p>
<h1 class="page-heading">Yomiwa</h1>
<p>
Japanese Optical Character Recognition / Dictionary app, available on iOS and Android:
</p>
<p>
<center><a class="badge" href="https://itunes.apple.com/us/app/yomiwa/id670931120?ls=1&mt=8"><img class="badge" src="{{ site.baseurl }}/res/Download_on_the_App_Store_Badge_US-UK_135x40.svg" alt="Available on the App Store"/></a>
<a href="https://play.google.com/store/apps/details?id=com.yomiwa.yomiwa&hl=en&utm_source=global_co&utm_medium=prtnr&utm_content=Mar2515&utm_campaign=PartBadge&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1"><img class="badge" alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/images/generic/en-play-badge.png" /></a>
</center>
</p>
<h1 class="page-heading">Transportation distance</h1>
		<p>
        Here is a matlab wrapper for the c++ code from Nicolas Bonneel available on <a href="http://people.seas.harvard.edu/~nbonneel/FastTransport/" target="_blank">this page</a>, which is a light adaptation of LEMON to solve the network simplex for bipartite graphs. I recommend using the source code, but you can also use one of the system specific compiled matlab function.
        </p>
		<p>
        Update 2015-05:
        <ul>
            <li>Corrected a bug that appears for highly degenerated problem that made the optimality check fail (leading to infinite cycling)</li>
            <li>Added an argument that allows to limit the maximum number of simplex pivot (defaults to infinity)</li>
        </ul>
        </p>
        <p><a href="{{ site.baseurl }}/res/code/mexEMD_source.zip">Source code</a></p>
        
        <p>Mac : <ul>
            <li><a href="{{ site.baseurl }}/res/code/mexEMD_OSX_64.zip">64bits version</a></li>
        </ul></p>
        
        <p>Linux :<ul>
            <li> <a href="{{ site.baseurl }}/res/code/mexEMD_linux_64.zip">64bits version (tested on ubuntu and centOS)</a></li>
            <li> <a href="{{ site.baseurl }}/res/code/mexEMD_linux_32.zip">32bits version (tested on ubuntu)</a></li>
                </ul></p>
        
        <p>Windows : <ul>
            <li>Coming soon</a></li>
        </ul></p>
        
</div>

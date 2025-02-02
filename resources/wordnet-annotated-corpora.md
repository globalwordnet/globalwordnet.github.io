---
layout: default
---

# Wordnet Annotated Corpora

<div class="table-responsive" style="max-width:855px">
    <table class="table table-sm">
        <thead>
            <tr>
                <th>Language</th>
                <th>Name</th>
                <th>SemCor Aligned</th>
                <th>Words</th>
                <th>Taggable</th>
                <th>Tagged</th>
                <th>Developer</th>
                <th>Contact</th>
                <th>Browse Online</th>
                <th>License</th>
                <th>Other Resources</th>
            </tr>
        </thead>
{% for corpus in site.data.wordnet_annotated_corpora %}
        <tr>
            <td>{{ corpus.language }}</td>
            <td>{{ corpus.name }}</td>
            <td>{{ corpus.semcor_aligned }}</td>
            <td>{{ corpus.words }}</td>
            <td>{{ corpus.taggable }}</td>
            <td>{{ corpus.tagged }}</td>
            <td>{{ corpus.developer }}</td>
            <td>{{ corpus.contact }}</td>
            <td>{{ corpus.browse_online }}</td>
            <td>{{ corpus.license }}</td>
            <td>{{ corpus.other_resources }}</td>
        </tr>
{% endfor %}
    </table>
</div>




Wordnet Annotated Corpora in the World

**Citations**

-   **bul** Svetla Koeva, Svetlozara Leseva, Ekaterina Tarpomanova,
    Borislav Rizov, Tsvetana Dimitrova, Hristina Kukova. [*Bulgarian
    Sense Annotated Corpus – Results and
    Achievements.*](http://hnk.ffzg.hr/fassbl2010/FASSBL7_2010_proceedings.pdf#page=41)
    In Tadić, M., Dimitrova- Vulchanova, M. and Koeva, S. (eds.):
    *Proceedings of the 7th International Conference of Formal
    Approaches to South Slavic and Balkan Languages (FASSBL-7)*, 4-6
    October 2010, Dubrovnik, Croatia, pp. 41-48. [ISBN
    978-953-55375-2-6](BookSources/9789535537526).
-   **baq** Eneko Agirre, Izaskun Aldezabal, Jone Etxeberria,
    EliIzagirre, Karmele Mendizabal, Eli Pociello, and Mikel
    Quintian. 2006. [*Improving the Basque WordNet by corpus
    annotation.*](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=E27A3EA564FCA581DDB44EF9B93D2EA3?doi=10.1.1.80.6766&rep=rep1&type=pdf)
    In Proceedings of the Third International WordNet Conference, pages
    287-290.
-   **dut** Vossen P., Görög, A., Laan, F., Van Gompel, M.,
    Izquierdo, R. , Van den Bosch, A. (2011). [*DutchSemCor: building a
    semantically annotated corpus for
    Dutch.*](http://www2.let.vu.nl/oz/cltl/dutchsemcor/docs/papers/DutchSemCor%20building%20a%20semantically%20annotated%20corpus%20for%20Dutch.pdf)
    *In: Proceedings of Electronic Lexicography in the 21st century: New
    Applications for new users (eLEX2011)*, Bled, Slovenia, November
    10-12, 2011
-   **eng** George A. Miller, Martin Chodorow, Shari Landes, Claudia
    Leacock, and Robert G. Thomas. 1994. [*Using a semantic concordance
    for sense
    identification.*](http://acl.ldc.upenn.edu/H/H94/H94-1046.pdf) In
    Proceedings of the ARPA Human Language Technology Workshop, pages
    240-243; George A. Miller, Claudia Leacock, Randee Tengi, and
    Ross T. Bunker. (1993). [*“A Semantic
    Concordance.”*](http://acl.ldc.upenn.edu/H/H93/H93-1061.pdf) In:
    Proceedings of the 3 DARPA Workshop on Human Language Technology
-   **eng** Ide, N. (2012). [*MultiMASC: An Open Linguistic
    Infrastructure for Language
    Research*](http://www.cs.vassar.edu/~ide/papers/comparative.pdf).
    Proceedings of the Fifth Workshop on Building and Using Comparable
    Corpora, held in conjunction with LREC 2012, Istanbul.
-   **eng** Benjamin Snyder and Martha Palmer (2005) [The English
    All-Words
    Task](http://www.cse.unt.edu/~rada/senseval/senseval3/proceedings/pdf/snyder.pdf),
    in Proceedings of the Third International Workshop on the Evaluation
    of Systems for the Semantic Analysis of Text (SENSEVAL-3), 2004
-   **ger** Verena Henrich, Erhard Hinrichs, and Tatiana Vodolazova:
    [*WebCAGe — A Web-Harvested Corpus Annotated with GermaNet
    Senses.*](http://aclweb.org/anthology/E/E12/E12-1039.pdf) *In
    Proceedings of the 13th Conference of the European Chapter of the
    Association for Computational Linguistics (EACL 2012)*, Avignon,
    France, April 2012, pp. 387-396.
-   **ita** Luisa Bentivogli, Emanuele Pianta and Marcello Ranieri
    [*MultiSemCor: an English Italian aligned corpus with a shared
    inventory of
    senses*](http://multisemcor.fbk.eu/papers/meaning2005.pdf) In
    Proceedings of the Meaning Workshop 2005, Trento, Italy, February
    3-4, 2005, p. 90; Luisa Bentivogli and Emanuele Pianta. 2005.
    [Exploiting parallel texts in the creation of multilingual
    semantically annotated resources: the multisemcor
    corpus.](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.149.3179&rep=rep1&type=pdf)
    Natural Language Engineering, 11(3):247�261.
-   **ita** Simonetta Montemagni, Francesco Barsotti, Marco Battista,
    Nicoletta Calzolari, Ornella Corazzari, Alessandro Lenci, Antonio
    Zampolli, Francesca Fanciulli, Maria Massetani, Remo Raffaelli,
    Roberto Basili, Maria Teresa Pazienza, Dario Saracino, Fabio
    Zanzotto, Nadia Mana, Fabio Pianesi, Rodolfo Delmonte, 2003.
    [“Building the Italian Syntactic-Semantic
    Treebank”](http://www.ilc.cnr.it/tressi_prg/papers/isst_kluwer_final_version.pdf),
    *in Anne Abeillé (a cura di), Building and using Parsed Corpora,
    Language and Speech series*, Kluwer, Dordrecht, pp. 189-210 ;
    Stefano Dei Rossi, Giulia Di Pietro, Maria Simi[Evalita
    2011:Description and Results of the SuperSense Tagging
    Task](http://www.evalita.it/sites/evalita.fbk.eu/files/working_notes2011/SST/SST_ORGANIZERS.pdf)
-   **jpn** Francis Bond, Timothy Baldwin, Richard Fothergill and
    Kiyotaka Uchimoto (2012) [*Japanese SemCor: A Sense-tagged Corpus of
    Japanese*](http://nlpwww.nict.go.jp/wn-ja/pubs/2012-gwc-jsemcor.pdf)
    in The 6th International Conference of the Global WordNet
    Association (GWC-2012), Matsue.
-   **rum** Monica Lupu, Diana Trandabat and Maria Husarciuc. [*A
    Romanian SemCor aligned to the English and Italian
    MultiSemCor*](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.148.7775&rep=rep1&type=pdf).
    In 1st ROMANCE FrameNet Workshop at EUROLAN 2005 Summer School,
    Proceedings, pages 20{27, Cluj-Napoca, Romania, July 2005.
-   **spa** Castellón I., Climent S., Coll-Florit M., Lloberes M. and
    Rigau G. [*Semantic Hand-Tagging of the SenSem Corpus Using Spanish
    WordNet
    Senses.*](http://www.google.com.sg/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&ved=0CC8QFjAA&url=http%3A%2F%2Fwww.paths-project.eu%2Feng%2Fcontent%2Fdownload%2F888%2F5626%2Fversion%2F2%2Ffile%2FGWN12.v10%2B.pdf&ei=3rAjUvLfAoLorQekz4CYBA&usg=AFQjCNEP8Vc6CnHyfmRIJeRr_4ujY97T5g&sig2=BifHvRiDZuWbWStiCddA9Q&bvm=bv.51495398,d.bmk&cad=rja)
    Proceedings of the 6th Global WordNet Conference (GWC’12), Matsue,
    Japan. January, 2012.

**References**

1.  [↑](#cite_ref-1) Both lexical and function words were subject to
    annotation
2.  [↑](#cite_ref-2) 282,503 tagged manually by two annotators, 400,000+
    by at least one annotator, and millions automatically
3.  [↑](#cite_ref-3) According to Bentivogli and Pianta (2005), 23,4% of
    Italian words still need to be tagged, so we can estimate (given
    that 92,820 is the 76,6%) the taggable words at 121,175

 

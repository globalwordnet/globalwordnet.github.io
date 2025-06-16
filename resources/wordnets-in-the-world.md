---
layout: default
custom_css: gwa
---

# Wordnets in the World

**Wordnets in the World**
<pre>{{ wordnet.language }}</pre>
<div class="table-responsive">
    <table class="table table-sm table-striped table-hover wordnets-table">
        <thead>
            <tr>
                <th>Language</th>
                <th>Resource Name</th>
               <th>Online</th>
               <th>Developer(s)</th>
                <th>Contact</th>
                <th>License</th>
                <th>Other</th>
            </tr>
        </thead>
        <tbody>
        {% for wordnet in site.data.wordnets %}
            <tr>
				<td>{% if wordnet.language.size > 5 %}
                       <span title="{{ wordnet.language  | join: ', ' }}">Multilingual</span>
                    {% else %}
                       {{ wordnet.language | join: ', ' }}
                    {% endif %}
               </td>
              <td>{% for name in wordnet.title %}
                     {% if name[1] != '' %}
                     <a href="{{ name[1] }}">{{ name[0] }}</a>
                     {% else %}
                     {{ name[0] }}
                     {% endif %}
                     {% unless forloop.last %}, {% endunless %}
                  {% endfor %}
	          </td>
			 <td>{% for name in wordnet.online %}
                     {% if name[1] != '' %}
                     <a href="{{ name[1] }}">{{ name[0] }}</a>
                     {% else %}
                     {{ name[0] }}
                     {% endif %}
                     {% unless forloop.last %}, {% endunless %}
                  {% endfor %}
	          </td>
			 <td>{% for name in wordnet.developer %}
                     {% if name[1] != '' %}
                     <a href="{{ name[1] }}">{{ name[0] }}</a>
                     {% else %}
                     {{ name[0] }}
                     {% endif %}
                     {% unless forloop.last %}, {% endunless %}
                  {% endfor %}
	          </td>
			 <td>{% for name in wordnet.contact %}
                     {% if name[1] != '' %}
                     <a href="{{ name[1] }}">{{ name[0] }}</a>
                     {% else %}
                     {{ name[0] }}
                     {% endif %}
                     {% unless forloop.last %}, {% endunless %}
                  {% endfor %}
	          </td>
			 <td>{% for name in wordnet.license %}
                     {% if name[1] != '' %}
                     <a href="{{ name[1] }}">{{ name[0] }}</a>
                     {% else %}
                     {{ name[0] }}
                     {% endif %}
                     {% unless forloop.last %}, {% endunless %}
                  {% endfor %}
	          </td>
			 <td>{% for name in wordnet.other %}
                     {% if name[1] != '' %}
                     <a href="{{ name[1] }}">{{ name[0] }}</a>
                     {% else %}
                     {{ name[0] }}
                     {% endif %}
                     {% unless forloop.last %}, {% endunless %}
                  {% endfor %}
	          </td>

			  
            </tr>
        {% endfor %}
        </tbody>
    </table>
</div>

Wordnets in the World

**Related Products**

|  |  |  |  |  |
|----|----|----|----|----|
| Product | Resource name | Owner(s) | Contact | Distributor |
| Multilingual Wordnet (over 100 languages) | UWN | [MPI, Germany](http://www.mpi-inf.mpg.de/) | [Gerard de Melo](http://www.lexvo.org/gdm/) | [use on line/download](http://www.mpi-inf.mpg.de/yago-naga/uwn/) (various licenses) |
| Domain lexicon | Wordnet Domains | [FBK, HLT Group, Trento, Italy](http://hlt.fbk.eu/) | [Bernardo Magnini](mailto:magnini@itc.it) | [Obtain Wordnet Domains](http://wndomains.fbk.eu/download.html) under [CC BY 3.0](http://creativecommons.org/licenses/by/3.0/) |
| German Thesaurus | OpenThesaurus | [Daniel Naber](http://www.danielnaber.de/) | [Daniel Naber](mailto:naber@danielnaber.de) | free download from [OpenThesaurus](http://www.openthesaurus.de/) |

Related Products

**Citations**

-   **als** Ervin Ruci (2008) [*On the current state of Albanet and
    related
    applications*](http://fjalnet.com/technicalreportalbanet.pdf),
    *Technical Report*, University of Vlora
-   **arb** Horacio Rodríguez, David Farwell, Javi Farreres, Manuel
    Bertran, Musa Alkhalifa, M. Antonia Martí, William Black, Sabri
    Elkateb, James Kirk, Adam Pease, Piek Vossen, and Christiane
    Fellbaum. [*Arabic WordNet: Current State and Future
    Extensions*](http://nlp.lsi.upc.edu/papers/rodriguez08.pdf) in:
    *Proceedings of the Fourth International GlobalWordNet Conference –
    GWC 2008*, Szeged, Hungary, January 22-25, 2008
-   **cat**, **eus**, **glg**, **spa**, Aitor Gonzalez-Agirre, Egoitz
    Laparra and German Rigau (2012) [*Multilingual Central Repository
    version 3.0: upgrading a very large lexical knowledge
    base.*](http://adimen.si.ehu.es/~rigau/publications/gwc12-glr.pdf)
    In Proceedings of the 6th Global WordNet Conference (GWC 2012)
    Matsue, Japan.
-   **eng** Christiane Fellbaum. (ed.) (1998) *WordNet: An Electronic
    Lexical Database*. Cambridge, MA: MIT Press; George A. Miller
    (1995). *WordNet: A Lexical Database for English.* Communications of
    the ACM Vol. 38, No. 11: 39-41.
-   **fas** Montazery, Mortaza and Heshaam Faili (2010) *Automatic
    Persian WordNet Construction*, the 23rd International conference on
    computational linguistics pp. 846–850
-   **fin** Lindén K., Carlson. L., (2010) *FinnWordNet — WordNet
    påfinska via översättning,LexicoNordica* — Nordic Journal of
    Lexicography, 17:119–140
-   **fre** Benoit Sagot and Darla Fišer (2008) *Building a free French
    wordnet from multilingual resources*, E. L. R. A. (ELRA) (ed.),
    Proceedings of the Sixth International Language Resources and
    Evaluation (LREC’08), Marrakech, Morocco
-   **fre** Q. Pradet, G. de Chalendar, J. Baguenier-Desormeaux (2014).
    *WoNeF, an improved, expanded and evaluated automatic French
    translation of WordNet*, In *Proceedings of the Seventh Global
    WordNet Conference*, Tartu, Estonia, January 25-29, 2014, 32-39
-   **heb** Noam Ordan and Shuly Wintner (2007) *Hebrew WordNet: a test
    case of aligning lexical databases across languages.* International
    Journal of Translation 19(1):39–58, 2007
-   **ita** Emanuele Pianta, Luisa Bentivogli and Christian
    Girardi. (2002) *MultiWordNet: Developing an Aligned Multilingual
    Database.* In *Proceedings of the First International Conference on
    Global WordNet*, Mysore, India, January 21-25, 2002, pp. 293-302.
-   **ind**,**zsm** Nurril Hirfana Mohamed Noor, Suerya Sapuan and
    Francis Bond (2011) [*Creating the open Wordnet
    Bahasa*](http://web.mysites.ntu.edu.sg/fcbond/open/pubs/2011-wn-bahasa.pdf)
    In *Proceedings of the 25th Pacific Asia Conference on Language,
    Information and Computation (PACLIC 25)* pages 258–267. Singapore
-   **jpn** Hitoshi Isahara, Francis Bond, Kiyotaka Uchimoto, Masao
    Utiyama and Kyoko Kanzaki (2008) [*Development of Japanese
    WordNet.*](http://nlpwww.nict.go.jp/wn-ja/pubs/2008-lrec-wn-ja-isahara.pdf)
    In LREC-2008, Marrakech.
-   **kur** P. Aliabadi, M. S. Ahmadi, S. Salavati, K. Sheykh Esmaili
    (2014). *Towards Building KurdNet, the Kurdish WordNet*, In
    *Proceedings of the Seventh Global WordNet Conference*, Tartu,
    Estonia, January 25-29, 2014, 1-6
-   **rom** Dan Tufiş, Verginica Barbu Mititelu, Dan Ştefănescu, Radu
    Ion, TheRomanian Wordnet in a Nutshell. Language and Evaluation,
    Springer, Vol. 47, no. 2, 2013, ISSN 1574-020X, DOI:
    10.1007/s10579-013-9230-7
-   **pol** Maciej Piasecki, Stanisław Szpakowicz and Bartosz
    Broda. (2009) [*A Wordnet from the Ground
    Up.*](http://www.plwordnet.pwr.wroc.pl/main/content/files/publications/A_Wordnet_from_the_Ground_Up.pdf)\]
    Wroclaw: Oficyna Wydawnicza Politechniki Wroclawskiej, Poland.
-   **por** Valeria de Paiva and Alexandre Rademaker (2012) *Revisiting
    a Brazilian wordnet.* In *Proceedings of Global Wordnet Conference*,
    Matsue. Global Wordnet Association. (also with Gerard de Melo’s
    contribution)
-   **sin** I. Wijesiri, M. Gallage, B. Gunathilaka, M. Lakjeewa, D.
    Wimalasuriya, G. Dias, R. Paranavithana, N. de Silva (2014).
    *Building a WordNet for Sinhala*, In *Proceedings of the Seventh
    Global WordNet Conference*, Tartu, Estonia, January 25-29, 2014,
    100-108
-   **tha** Thoongsup S., Charoenporn T., Robkop K., Sinthurahat T.,
    Mokarat C., Sornlertlamvanich V., Isahara H. (2009) *Thai Wordnet
    Construction*, Proceedings of The 7th Workshop on Asian Language
    Resources (ALR7), Joint conference of the 47th Annual Meeting of the
    Association for Computational Linguistics (ACL) and the 4th
    International Joint Conference on Natural Language Processing
    (IJCNLP) Suntec, Singapore
-   **uz** (or uzn) A. Agostini, T. Usmanov, U. Khamdamov, N.
    Abdurakhmonova, and M. Mamasaidov (2021) *[UzWordnet: A Lexical-
    Semantic Database for the Uzbek
    Language](https://uzwordnet.ldkr.org/storage/references/Agostini2021GWC.pdf)*.
    In S. Bosch, C. Fellbaum, M. Griesel, A. Rademaker and P. Vossen,
    editors, Proceedings of the Eleventh International Global Wordnet
    Conference (GWC-2021), pp. 8–19, Potchefstroom, South Africa,
    January 2021.

 

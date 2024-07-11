BestIR is a heterogeneous benchmark for robustness in IR.
More complete content coming soon.




#### Benchmark datasets for studying adversarial robustness
\#Q$_{\mathrm{eval}}$ denotes the number of queries for evaluation.

<table border="1">
    <thead>
        <tr>
            <th>Dataset</th>
            <th>#Document</th>
            <th>#Q<sub>train</sub></th>
            <th>#Q<sub>dev</sub></th>
            <th>#Q<sub>eval</sub></th>
            <th>Links</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>MS MARCO document</td>
            <td>3.2M</td>
            <td>370K</td>
            <td>5,193</td>
            <td>5,793</td>
            <td><a href="https://openreview.net/pdf?id=Hk1iOLcle">Paper</a></td>
        </tr>
        <tr>
            <td>MS MARCO passage</td>
            <td>8.8M</td>
            <td>500K</td>
            <td>6,980</td>
            <td>6,837</td>
            <td><a href="https://openreview.net/pdf?id=Hk1iOLcle">Paper</a></td>
        </tr>
        <tr>
            <td>Clueweb09-B</td>
            <td>50M</td>
            <td>150</td>
            <td>-</td>
            <td>-</td>
            <td><a href="https://lemurproject.org/clueweb09/">Website</a></td>
        </tr>
        <tr>
            <td>Natural Questions</td>
            <td>21M</td>
            <td>60K</td>
            <td>8.8K</td>
            <td>3.6K</td>
            <td><a href="https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl_a_00276/1923288/tacl_a_00276.pdf">Paper</a></td>
        </tr>
        <tr>
            <td>TriviaQA</td>
            <td>21M</td>
            <td>60K</td>
            <td>8.8K</td>
            <td>11.3K</td>
            <td><a href="https://arxiv.org/pdf/1705.03551">Paper</a></td>
        </tr>
        <tr>
            <td>TREC DL19</td>
            <td>-</td>
            <td>-</td>
            <td>43</td>
            <td>-</td>
            <td><a href="https://arxiv.org/pdf/2003.07820">Paper</a></td>
        </tr>
        <tr>
            <td>TREC DL20</td>
            <td>-</td>
            <td>-</td>
            <td>54</td>
            <td>-</td>
            <td><a href="https://arxiv.org/pdf/2102.07662">Paper</a></td>
        </tr>
        <tr>
            <td>TREC MB14</td>
            <td>-</td>
            <td>-</td>
            <td>50</td>
            <td>-</td>
            <td><a href="https://trec.nist.gov/pubs/trec23/papers/overview-microblog.pdf">Paper</a></td>
        </tr>
        <tr>
            <td>ASRC</td>
            <td>1,279</td>
            <td>-</td>
            <td>31</td>
            <td>-</td>
            <td><a href="https://dl.acm.org/doi/abs/10.1145/3077136.3080785">Paper</a></td>
        </tr>
        <tr>
            <td>Q-MS MARCO</td>
            <td>-</td>
            <td>-</td>
            <td>4,000</td>
            <td>-</td>
            <td><a href="https://dl.acm.org/doi/pdf/10.1145/3539618.3591777">Paper</a></td>
        </tr>
        <tr>
            <td>Q-Clueweb09</td>
            <td>-</td>
            <td>-</td>
            <td>292</td>
            <td>-</td>
            <td><a href="https://dl.acm.org/doi/pdf/10.1145/3539618.3591777">Paper</a></td>
        </tr>
        <tr>
            <td>DARA</td>
            <td>164K</td>
            <td>50K</td>
            <td>3,490</td>
            <td>3,489</td>
            <td><a href="https://arxiv.org/pdf/2307.16816">Paper</a></td>
        </tr>
    </tbody>
</table>



#### Benchmark datasets for studying adversarial robustness
\#Document denotes the number of documents in corpus; \#Q$_{\mathrm{train}}$ denotes the number of queries for training; \#Q$_{\mathrm{dev}}$ denotes the number of queries for development; \#Q$_{\mathrm{eval}}$ denotes the number of queries for evaluation.





<table border="1">
    <thead>
        <tr>
            <th>Type</th>
            <th>Dataset</th>
            <th>#Corpus</th>
            <th colspan="4">Links</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th>Adaptation to new corpus</th>
            <td>BEIR</td>
            <td>18</td>
            <td colspan="4"><a href="https://arxiv.org/abs/2104.08663">Paper</a></td>
        </tr>
        <tr>
            <th rowspan="5">Updates to a corpus</th>
            <th>Dataset</th>
            <th>#Document</th>
            <th>#Q<sub>train</sub></th>
            <th>#Q<sub>dev</sub></th>
            <th>#Q<sub>eval</sub></th>
            <th>Links</th>
        </tr>
        <tr>
            <td>CDI-MS</td>
            <td>3.2M</td>
            <td>370K</td>
            <td>5,193</td>
            <td>5,793</td>
            <td><a href="https://dl.acm.org/doi/abs/10.1145/3583780.3614821">Paper</a></td>
        </tr>
        <tr>
            <td>CDI-NQ</td>
            <td>8.8M</td>
            <td>500K</td>
            <td>6,980</td>
            <td>6,837</td>
            <td><a href="https://dl.acm.org/doi/abs/10.1145/3583780.3614821">Paper</a></td>
        </tr>
        <tr>
            <td>LL-LoTTE</td>
            <td>21M</td>
            <td>60K</td>
            <td>8.8K</td>
            <td>3.6K</td>
            <td><a href="https://dl.acm.org/doi/abs/10.1145/3583780.3614947">Paper</a></td>
        </tr>
        <tr>
            <td>LL-MultiCPR</td>
            <td>21M</td>
            <td>60K</td>
            <td>8.8K</td>
            <td>3.6K</td>
            <td><a href="https://dl.acm.org/doi/abs/10.1145/3583780.3614947">Paper</a></td>
        </tr>
    </tbody>
</table>




#### Benchmark datasets for unseen queries
\#Q$_{\mathrm{eval}}$ denotes the number of queries for evaluation.

<table border="1">
    <thead>
        <tr>
            <th>Type</th>
            <th>Dataset</th>
            <th>#Q<sub>eval</sub></th>
            <th>Links</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <th rowspan="9">Query variation</th>
            <td>DL-Typo</td>
            <td>60</td>
            <td><a href="https://arxiv.org/pdf/2204.00716">Paper</a></td>
        </tr>
        <tr>
            <td>noisy-MS MARCO</td>
            <td>5.6k</td>
            <td><a href="https://arxiv.org/abs/2304.03401">Paper</a></td>
        </tr>
        <tr>
            <td>rewrite-MS MARCO</td>
            <td>5.6k</td>
            <td><a href="https://arxiv.org/abs/2304.03401">Paper</a></td>
        </tr>
        <tr>
            <td>noisy-NQ</td>
            <td>2k</td>
            <td><a href="https://arxiv.org/abs/2304.03401">Paper</a></td>
        </tr>
        <tr>
            <td>noisy-TQA</td>
            <td>3k</td>
            <td><a href="https://arxiv.org/abs/2304.03401">Paper</a></td>
        </tr>
        <tr>
            <td>noisy-ORCAS</td>
            <td>20k</td>
            <td><a href="https://arxiv.org/abs/2304.03401">Paper</a></td>
        </tr>
        <tr>
            <td>variations-ANTIQUE</td>
            <td>2k</td>
            <td><a href="https://arxiv.org/pdf/2111.13057">Paper</a></td>
        </tr>
        <tr>
            <td>variations-TREC19</td>
            <td>430</td>
            <td><a href="https://arxiv.org/pdf/2111.13057">Paper</a></td>
        </tr>
        <tr>
            <td>Zhuang et al., 2021</td>
            <td>41k</td>
            <td><a href="https://arxiv.org/pdf/2108.12139">Paper</a></td>
        </tr>
        <tr>
            <th rowspan="2">Unseen query type</th>
            <td>MS MARCO</td>
            <td>15k</td>
            <td><a href="https://openreview.net/pdf?id=Hk1iOLcle">Paper</a></td>
        </tr>
        <tr>
            <td>L4</td>
            <td>10k</td>
            <td><a href="https://aclanthology.org/P08-1082.pdf">Paper</a></td>
        </tr>
    </tbody>
</table>

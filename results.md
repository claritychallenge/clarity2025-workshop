---
layout: page
title: CPC3 Results
---

<div class="panel panel-default">
<div class="panel-body">

<div class="bg-light py-1">
      <div class="container page-content">
          <article>

Results of the <a href="https://claritychallenge.org/docs/cpc3/cpc3_intro">3rd Clarity Prediction Challenge</a> are shown below for all submitted systems. For RMSE scores, small values are best. For correlation coefficients (corr), large numbers are best. The table also identifies which systems are intrusive and which are non-intrusive. The system labeled 'prior' simply returns the training set average sentence intelligibility for all sentences. The beHASPI system is the baseline supplied by the organisers.

<table
  class="datatable table table-hover table-condensed"
  data-bar-hline="true"
  data-chart-default-mode="bar"
  data-chart-modes="bar,scatter"
  data-id-field="name"
  data-pagination="false"
  data-rank-mode="grouped_muted"
  data-row-highlighting="true"
  data-bar-height="340"
  data-show-chart="true"
  data-show-rank="true"
  data-sort-name="eval_rmse"
  data-sort-order="inc"
  data-scatter-x="dev_rmse"
  data-scatter-y="eval_rmse"
  data-line-yaxis-beginatzero="true"
>
  <thead>
    <tr>
      <th class="sep-left-cell text-center" data-rank="true">Rank</th>
      <th
        class="sep-left-cell text-center"
        data-field="name"
        data-sortable="true"
        data-value-type="str"
        id="system"
      >
        System
      </th>
      <th
        class="sep-left-cell text-center"
        data-field="paper"
        data-sortable="true"
        data-value-type="str"
        id="team"
      >
        Paper
      </th>
       <th
        class="sep-left-cell text-center"
        data-chartable="true"
        data-field="intrusive"
        data-sortable="true"
        data-value-type="bool"
        id="intrusive"
      >
        Intrusive?
      </th>
       <th
        class="sep-left-cell text-center"
        data-chartable="true"
        data-field="dev_rmse"
        data-sortable="true"
        data-value-type="float1"
      >
        Dev RMSE
      </th>
      <th
        class="sep-left-cell text-center"
        data-chartable="true"
        data-field="eval_rmse"
        data-sortable="true"
        data-value-type="float1"
      >
        Eval RMSE
      </th>
      <th
        class="sep-right-cell sep-left-cell text-center"
        data-chartable="true"
        data-field="eval_corr"
        data-sortable="true"
        data-value-type="float2"
      >
        Eval Corr
      </th>

    </tr>
  </thead>

  <tbody>

    <tr>
      <td></td>
      <td>E025</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/yu25_clarity.html">[paper]</a> </td>
      <td>Yes</td>
      <td>22.36</td>
      <td>24.98</td>
      <td>0.80</td>
    </tr>

    <tr>
      <td></td>
      <td>E019</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/buragohain25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>21.87</td>
      <td>25.31</td>
      <td>0.79</td>
    </tr>

    <tr>
      <td></td>
      <td>E011a</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/zezario25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>22.80</td>
      <td>25.54</td>
      <td>0.79</td>
    </tr>

    <tr>
      <td></td>
      <td>E020a</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/zhou25_clarity.html">[paper]</a> </td>
      <td>Yes</td>
      <td>23.15</td>
      <td>25.60</td>
      <td>0.78</td>
    </tr>

    <tr>
      <td></td>
      <td>E014</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/jeon25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>22.95</td>
      <td>25.82</td>
      <td>0.78</td>
    </tr>

    <tr>
      <td></td>
      <td>E011c</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/zezario25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>22.89</td>
      <td>25.83</td>
      <td>0.79</td>
    </tr>

    <tr>
      <td></td>
      <td>E032</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/jin25_clarity.html">[paper]</a> </td>
      <td>Yes (Text)</td>
      <td>23.60</td>
      <td>25.99</td>
      <td>0.78</td>
    </tr>

    <tr>
      <td></td>
      <td>E020b</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/zhou25_clarity.html">[paper]</a> </td>
      <td>Yes</td>
      <td>23.47</td>
      <td>26.02</td>
      <td>0.78</td>
    </tr>

    <tr>
      <td></td>
      <td>E011b</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/zezario25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>22.89</td>
      <td>26.12</td>
      <td>0.78</td>
    </tr>

    <tr>
      <td></td>
      <td>E020c</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/mawalim25_clarity.html">[paper]</a> </td>
      <td>Yes</td>
      <td>24.81</td>
      <td>26.14</td>
      <td>0.77</td>
    </tr>

    <tr>
      <td></td>
      <td>E017</td>
      <td> <a href="./papers/CPC3_E017_report.pdf">[paper]</a> </td>
      <td>Yes</td>
      <td>24.05</td>
      <td>26.30</td>
      <td>0.77</td>
    </tr>

    <tr>
      <td></td>
      <td>E024b</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/lin25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>24.74</td>
      <td>26.58</td>
      <td>0.77</td>
    </tr>

    <tr>
      <td></td>
      <td>E026</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/huckvale25_clarity.html">[paper]</a> </td>
      <td>Yes</td>
      <td>24.64</td>
      <td>26.90</td>
      <td>0.76</td>
    </tr>

    <tr>
      <td></td>
      <td>E039</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/drgas5_clarity.html">[paper]</a> </td>
      <td>Yes</td>
      <td>25.61</td>
      <td>27.00</td>
      <td>0.76</td>
    </tr>

    <tr>
      <td></td>
      <td>E024a</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/lin25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>24.18</td>
      <td>27.11</td>
      <td>0.76</td>
    </tr>

    <tr>
      <td></td>
      <td>E038</td>
      <td> <a href="./papers/CPC3_E038_report.pdf">[paper]</a> </td>
      <td>Yes</td>
      <td>24.88</td>
      <td>27.82</td>
      <td>0.74</td>
    </tr>

    <tr>
      <td></td>
      <td>E035</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/saddler25_clarity.html">[paper]</a> </td>
      <td>Yes</td>
      <td></td>
      <td>27.87</td>
      <td>0.75</td>
    </tr>

    <tr>
      <td></td>
      <td>E012</td>
      <td> <a href="./papers/CPC3_E012_report.pdf">[paper]</a> </td>
      <td>No</td>
      <td>26.28</td>
      <td>29.07</td>
      <td>0.75</td>
    </tr>

    <tr>
      <td></td>
      <td>HASPI</td>
      <td> </td>
      <td>Yes</td>
      <td>28.00</td>
      <td>29.47</td>
      <td>0.70</td>
    </tr>

    <tr>
      <td></td>
      <td>E020c-ni</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/mawalim25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>30.16</td>
      <td>32.74</td>
      <td>0.65</td>
    </tr>

    <tr>
      <td></td>
      <td>E022a</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/chen25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>31.11</td>
      <td>33.97</td>
      <td>0.57</td>
    </tr>

    <tr>
      <td></td>
      <td>E022b</td>
      <td> <a href="https://www.isca-archive.org/clarity_2025/chen25_clarity.html">[paper]</a> </td>
      <td>No</td>
      <td>33.10</td>
      <td>35.48</td>
      <td>0.56</td>
    </tr>

    <tr>
      <td></td>
      <td>Prior</td>
      <td> </td>
      <td>No</td>
      <td>40.20</td>
      <td>41.33</td>
      <td> </td>
    </tr>

  </tbody>
</table>

<header>
    <h1>Prizes</h1>
  </header>

  <section>
    <br />

<p>The Hearing Industry Research Consortium best system prizes were awarded to the following teams.</p>

<!------------------------->

<div class="card  m-3">
<div class="card-body">

First place prize,  1000 GPB
<table>
<tbody>

<tr>
<td style="padding: 5px;"> <span class="author">Hanlin Yu<sup>1</sup>, Haoshuai Zhou<sup>2</sup>, Linkai Li<sup>2,3</sup>, Boxuan Cao<sup>2</sup>, Changgeng Mo<sup>2</sup>, Shan Xiang Wang<sup>3</sup></span> <i>( <sup>1</sup>University of British Columbia,Canada; <sup>2</sup>Orka Labs Inc., China; <sup>3</sup>Stanford University, US)</i>, for their work: <br/> <b> Intrusive Intelligibility Prediction with ASR Encoders
  </b><a href="https://www.isca-archive.org/clarity_2025/yu25_clarity.html">[Paper]</a> </td>
</tr>

</tbody>
</table>

</div> </div>

<!------------------------->

<div class="card  m-3">
<div class="card-body">

Second place prize,  500 GPB
<table>
<tbody>

<tr>

<td style="padding: 5px;"> <span class="author">Rantu Buragohain<sup>1</sup>, Jejariya Ajaybhai<sup>1</sup>, Aashish Kumar Singh<sup>1</sup>, Karan Nathwani<sup>1</sup>, Sunil Kumar
Kopparapu<sup>2</sup></span> <i>( <sup>1</sup>Indian Institute of Technology Jammu, India; <sup>2</sup>Tata Consultancy Services Limited Mumbai, India)</i>, for their work: <br/> <b> Non-Intrusive Speech Intelligibility Prediction Using Whisper ASR and Wavelet Scattering Embeddings for Hearing-Impaired Individuals  </b><a href="https://www.isca-archive.org/clarity_2025/buragohain25_clarity.html">[Paper]</a></td>

</tr>

</tbody>
</table>

</div> </div>
<!------------------------->

<div class="card  m-3">
<div class="card-body">

Third place prize,  250 GPB
<table>
<tbody>

<tr>

<td style="padding: 5px;"><span class="author"> Ryandhimas E. Zezario<sup>1</sup>, Szu-Wei Fu<sup>2</sup>, Dyah A.M.G. Wisnu<sup>1,3</sup>, Hsin-Min Wang<sup>1</sup>, Yu Tsao<sup>1</sup></span> <i>( <sup>1</sup>Academia Sinica; <sup>2</sup>NVIDIA; <sup>3</sup>National Chengchi University)</i>, for their work: <br /> <b> Non-Intrusive Multi-Branch Speech Intelligibility Prediction using Multi-Stage Training  </b> <a href="https://www.isca-archive.org/clarity_2025/zezario25_clarity.html">[Paper]</a>  </td>

</tr>

</tbody>
</table>

</div> </div>

<!------------------------->

<p/>

<p>Congratulations to all our winners!</p>

<br />
<a href="#TOP">[TOP]</a>
<p />
<br />
<br />

  </section>

</article>

</div>

</div>

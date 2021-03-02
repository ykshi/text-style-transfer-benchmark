# Text Style Transfer Benchmark

This benchmark is built for neural text style transfer. We are still collecting the relevant results and paper, ***if you want to add your own paper on this benchmark, feel free to contact us*** by sending mail to `szha2609 [at] uni.sydney.edu.au` or `ykshi.1991 [at] foxmail.com`, we will update your data ASAP. 

## Yelp Dataset

<table class="tg">
<thead>
  <tr>
    <th class="tg-9wq8">Dataset:&nbsp;Yelp</th>
    <th class="tg-9wq8" colspan="5">Content Preservation</th>
    <th class="tg-9wq8" colspan="3">Naturalness</th>
    <th class="tg-9wq8" colspan="2">Transfer Intensity</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-9wq8">Model</td>
    <td class="tg-9wq8">WMD</td>
    <td class="tg-9wq8">BLEU</td>
    <td class="tg-9wq8">B-P</td>
    <td class="tg-9wq8">B-R</td>
    <td class="tg-9wq8">B-F1</td>
    <td class="tg-9wq8">N-A</td>
    <td class="tg-9wq8">N-C</td>
    <td class="tg-9wq8">N-D</td>
    <td class="tg-9wq8">ACCU</td>
    <td class="tg-9wq8">EMD</td>
  </tr>
   <td class="tg-9wq8"><a href="https://arxiv.org/pdf/2102.00769.pdf" target="_blank" rel="noopener noreferrer">GTAE</a>(shi2021gtae)</td>
    <td class="tg-9wq8">0.1027</td>
    <td class="tg-9wq8">64.83</td>
    <td class="tg-9wq8">0.6991</td>
    <td class="tg-9wq8">0.7303</td>
    <td class="tg-9wq8">0.7149</td>
    <td class="tg-9wq8">0.6178</td>
    <td class="tg-9wq8">0.9272</td>
    <td class="tg-9wq8">0.6644</td>
    <td class="tg-9wq8">0.8870</td>
    <td class="tg-9wq8">0.8505</td>
  </tr>
  <td class="tg-9wq8"><a href="http://papers.nips.cc/paper/7959-unsupervised-text-style-transfer-using-language-models-as-discriminators.pdf" target="_blank" rel="noopener noreferrer">Language-Discriminator</a>(yang2018)</td>
    <td class="tg-9wq8">0.1014</td>
    <td class="tg-9wq8">63.77</td>
    <td class="tg-9wq8">0.7292</td>
    <td class="tg-9wq8">0.7329</td>
    <td class="tg-9wq8">0.7314</td>
    <td class="tg-9wq8">0.5886</td>
    <td class="tg-9wq8">0.9074</td>
    <td class="tg-9wq8">0.6389</td>
    <td class="tg-9wq8">0.8940</td>
    <td class="tg-9wq8">0.8559</td>
  </tr>
   <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1810.06526" target="_blank" rel="noopener noreferrer">Struct</a>(tian2018)</td>
    <td class="tg-9wq8">0.1224</td>
    <td class="tg-9wq8">61.98</td>
    <td class="tg-9wq8">0.7174</td>
    <td class="tg-9wq8">0.7220</td>
    <td class="tg-9wq8">0.7200</td>
    <td class="tg-9wq8">0.6205</td>
    <td class="tg-9wq8">0.9261</td>
    <td class="tg-9wq8">0.7002</td>
    <td class="tg-9wq8">0.8960</td>
    <td class="tg-9wq8">0.8574</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1905.05621" target="_blank" rel="noopener noreferrer">StyleTrans-multi</a>(dai2019)</td>
    <td class="tg-9wq8">0.1536</td>
    <td class="tg-9wq8">63.08</td>
    <td class="tg-9wq8">0.7145</td>
    <td class="tg-9wq8">0.7203</td>
    <td class="tg-9wq8">0.7175</td>
    <td class="tg-9wq8">0.6133</td>
    <td class="tg-9wq8">0.9102</td>
    <td class="tg-9wq8">0.6909</td>
    <td class="tg-9wq8">0.8730</td>
    <td class="tg-9wq8">0.8316</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1905.10060" target="_blank" rel="noopener noreferrer">DualRL</a>(luo2019)</td>
    <td class="tg-9wq8">0.1692</td>
    <td class="tg-9wq8">59.01</td>
    <td class="tg-9wq8">0.7125</td>
    <td class="tg-9wq8">0.6988</td>
    <td class="tg-9wq8">0.7057</td>
    <td class="tg-9wq8">0.5517</td>
    <td class="tg-9wq8">0.8996</td>
    <td class="tg-9wq8">0.6768</td>
    <td class="tg-9wq8">0.9050</td>
    <td class="tg-9wq8">0.8675</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1809.00794" target="_blank" rel="noopener noreferrer">Texar</a>(hu2018)</td>
    <td class="tg-9wq8">0.1921</td>
    <td class="tg-9wq8">57.82</td>
    <td class="tg-9wq8">--</td>
    <td class="tg-9wq8">--</td>
    <td class="tg-9wq8">--</td>
    <td class="tg-9wq8">0.6934</td>
    <td class="tg-9wq8">0.9373</td>
    <td class="tg-9wq8">0.7066</td>
    <td class="tg-9wq8">0.8850</td>
    <td class="tg-9wq8">0.8429</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1905.05621" target="_blank" rel="noopener noreferrer">StyleTrans-cond</a>(dai2019)</td>
    <td class="tg-9wq8">0.2223</td>
    <td class="tg-9wq8">53.28</td>
    <td class="tg-9wq8">0.6205</td>
    <td class="tg-9wq8">0.6475</td>
    <td class="tg-9wq8">0.6341</td>
    <td class="tg-9wq8">0.6312</td>
    <td class="tg-9wq8">0.9109</td>
    <td class="tg-9wq8">0.6654</td>
    <td class="tg-9wq8">0.9290</td>
    <td class="tg-9wq8">0.8815</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1808.07894" target="_blank" rel="noopener noreferrer">UnsuperMT</a>(zhang2018)</td>
    <td class="tg-9wq8">0.2450</td>
    <td class="tg-9wq8">46.25</td>
    <td class="tg-9wq8">0.6060</td>
    <td class="tg-9wq8">0.6206</td>
    <td class="tg-9wq8">0.6134</td>
    <td class="tg-9wq8">0.5755</td>
    <td class="tg-9wq8">0.9040</td>
    <td class="tg-9wq8">0.6625</td>
    <td class="tg-9wq8">0.9770</td>
    <td class="tg-9wq8">0.9372</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1805.05181" target="_blank" rel="noopener noreferrer">UnpairedRL</a>(xu2018)</td>
    <td class="tg-9wq8">0.3122</td>
    <td class="tg-9wq8">46.09</td>
    <td class="tg-9wq8">0.4504</td>
    <td class="tg-9wq8">0.4709</td>
    <td class="tg-9wq8">0.4612</td>
    <td class="tg-9wq8">0.7136</td>
    <td class="tg-9wq8">0.9035</td>
    <td class="tg-9wq8">0.6493</td>
    <td class="tg-9wq8">0.5340</td>
    <td class="tg-9wq8">0.4989</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_Template</a>(li2018)</td>
    <td class="tg-9wq8">0.4156</td>
    <td class="tg-9wq8">57.10</td>
    <td class="tg-9wq8">0.4970</td>
    <td class="tg-9wq8">0.5406</td>
    <td class="tg-9wq8">0.5185</td>
    <td class="tg-9wq8">0.6370</td>
    <td class="tg-9wq8">0.8984</td>
    <td class="tg-9wq8">0.6299</td>
    <td class="tg-9wq8">0.8410</td>
    <td class="tg-9wq8">0.7948</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_DeleteOnly</a>(li2018)</td>
    <td class="tg-9wq8">0.4538</td>
    <td class="tg-9wq8">34.53</td>
    <td class="tg-9wq8">0.4158</td>
    <td class="tg-9wq8">0.4823</td>
    <td class="tg-9wq8">0.4490</td>
    <td class="tg-9wq8">0.6345</td>
    <td class="tg-9wq8">0.9072</td>
    <td class="tg-9wq8">0.5511</td>
    <td class="tg-9wq8">0.8750</td>
    <td class="tg-9wq8">0.8297</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_DeleteRetrieve</a>(li2018)</td>
    <td class="tg-9wq8">0.4605</td>
    <td class="tg-9wq8">36.72</td>
    <td class="tg-9wq8">0.4268</td>
    <td class="tg-9wq8">0.4799</td>
    <td class="tg-9wq8">0.4534</td>
    <td class="tg-9wq8">0.6564</td>
    <td class="tg-9wq8">0.9359</td>
    <td class="tg-9wq8">0.5620</td>
    <td class="tg-9wq8">0.9010</td>
    <td class="tg-9wq8">0.8550</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="http://papers.nips.cc/paper/7259-style-transfer-from-non-parallel-text-by-cross-alignment.pdf" target="_blank" rel="noopener noreferrer">CAAE</a>(shen2017)</td>
    <td class="tg-9wq8">0.5130</td>
    <td class="tg-9wq8">20.74</td>
    <td class="tg-9wq8">0.3585</td>
    <td class="tg-9wq8">0.3825</td>
    <td class="tg-9wq8">0.3710</td>
    <td class="tg-9wq8">0.4139</td>
    <td class="tg-9wq8">0.7006</td>
    <td class="tg-9wq8">0.5999</td>
    <td class="tg-9wq8">0.7490</td>
    <td class="tg-9wq8">0.7029</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1901.11333" target="_blank" rel="noopener noreferrer">IMaT</a>(jin2019)</td>
    <td class="tg-9wq8">0.5571</td>
    <td class="tg-9wq8">16.92</td>
    <td class="tg-9wq8">0.4750</td>
    <td class="tg-9wq8">0.4249</td>
    <td class="tg-9wq8">0.4501</td>
    <td class="tg-9wq8">0.4878</td>
    <td class="tg-9wq8">0.8407</td>
    <td class="tg-9wq8">0.6691</td>
    <td class="tg-9wq8">0.8710</td>
    <td class="tg-9wq8">0.8198</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPDFInterstitial/17015/15745" target="_blank" rel="noopener noreferrer">Multi_Decoder</a>(fu2018)</td>
    <td class="tg-9wq8">0.5799</td>
    <td class="tg-9wq8">24.91</td>
    <td class="tg-9wq8">0.3117</td>
    <td class="tg-9wq8">0.3315</td>
    <td class="tg-9wq8">0.3223</td>
    <td class="tg-9wq8">0.4829</td>
    <td class="tg-9wq8">0.8394</td>
    <td class="tg-9wq8">0.6365</td>
    <td class="tg-9wq8">0.6810</td>
    <td class="tg-9wq8">0.6340</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://www.aclweb.org/anthology/P19-1194.pdf" target="_blank" rel="noopener noreferrer">FineGrained-0.7</a>(luo2019)</td>
    <td class="tg-9wq8">0.6239</td>
    <td class="tg-9wq8">11.36</td>
    <td class="tg-9wq8">0.4023</td>
    <td class="tg-9wq8">0.3404</td>
    <td class="tg-9wq8">0.3717</td>
    <td class="tg-9wq8">0.3665</td>
    <td class="tg-9wq8">0.7125</td>
    <td class="tg-9wq8">0.5332</td>
    <td class="tg-9wq8">0.3960</td>
    <td class="tg-9wq8">0.3621</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://www.aclweb.org/anthology/P19-1194.pdf" target="_blank" rel="noopener noreferrer">FineGrained-0.9</a>(luo2019)</td>
    <td class="tg-9wq8">0.6251</td>
    <td class="tg-9wq8">11.07</td>
    <td class="tg-9wq8">0.4030</td>
    <td class="tg-9wq8">0.3389</td>
    <td class="tg-9wq8">0.3713</td>
    <td class="tg-9wq8">0.3668</td>
    <td class="tg-9wq8">0.7148</td>
    <td class="tg-9wq8">0.5231</td>
    <td class="tg-9wq8">0.4180</td>
    <td class="tg-9wq8">0.3926</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://www.aclweb.org/anthology/P19-1194.pdf" target="_blank" rel="noopener noreferrer">FineGrained-0.5</a>(luo2019)</td>
    <td class="tg-pb0m">0.6252</td>
    <td class="tg-pb0m">11.72</td>
    <td class="tg-pb0m">0.3994</td>
    <td class="tg-pb0m">0.3436</td>
    <td class="tg-pb0m">0.3718</td>
    <td class="tg-pb0m">0.3608</td>
    <td class="tg-pb0m">0.7254</td>
    <td class="tg-pb0m">0.5395</td>
    <td class="tg-pb0m">0.3280</td>
    <td class="tg-pb0m">0.2985</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.09000" target="_blank" rel="noopener noreferrer">BackTranslation</a>(prabhumoye2018)</td>
    <td class="tg-9wq8">0.7566</td>
    <td class="tg-9wq8">2.81</td>
    <td class="tg-9wq8">0.2405</td>
    <td class="tg-9wq8">0.2024</td>
    <td class="tg-9wq8">0.2220</td>
    <td class="tg-9wq8">0.3686</td>
    <td class="tg-9wq8">0.5392</td>
    <td class="tg-9wq8">0.4754</td>
    <td class="tg-9wq8">0.9500</td>
    <td class="tg-9wq8">0.9117</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPDFInterstitial/17015/15745" target="_blank" rel="noopener noreferrer">Style_Emb</a>(fu2018)</td>
    <td class="tg-9wq8">0.8796</td>
    <td class="tg-9wq8">3.24</td>
    <td class="tg-9wq8">0.0166</td>
    <td class="tg-9wq8">0.0673</td>
    <td class="tg-9wq8">0.0429</td>
    <td class="tg-9wq8">0.5788</td>
    <td class="tg-9wq8">0.9075</td>
    <td class="tg-9wq8">0.6450</td>
    <td class="tg-9wq8">0.4490</td>
    <td class="tg-9wq8">0.4119</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_RetrieveOnly</a>(li2018)</td>
    <td class="tg-9wq8">0.8990</td>
    <td class="tg-9wq8">2.62</td>
    <td class="tg-9wq8">0.1368</td>
    <td class="tg-9wq8">0.1818</td>
    <td class="tg-9wq8">0.1598</td>
    <td class="tg-9wq8">0.8067</td>
    <td class="tg-9wq8">0.9717</td>
    <td class="tg-9wq8">0.7211</td>
    <td class="tg-9wq8">0.9610</td>
    <td class="tg-9wq8">0.9010</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="http://proceedings.mlr.press/v80/zhao18b/zhao18b.pdf" target="_blank" rel="noopener noreferrer">ARAE</a>(zhao2018)</td>
    <td class="tg-9wq8">0.9047</td>
    <td class="tg-9wq8">5.95</td>
    <td class="tg-9wq8">0.1680</td>
    <td class="tg-9wq8">0.1478</td>
    <td class="tg-9wq8">0.1584</td>
    <td class="tg-9wq8">0.4476</td>
    <td class="tg-9wq8">0.8120</td>
    <td class="tg-9wq8">0.6969</td>
    <td class="tg-9wq8">0.8278</td>
    <td class="tg-9wq8">0.7880</td>
  </tr>
</tbody>
</table>




## Political Slant Dataset

<table class="tg">
<thead>
  <tr>
    <th class="tg-wa1i">Dataset:&nbsp;&nbsp;&nbsp;Political</th>
    <th class="tg-wa1i" colspan="5">Content Preservation</th>
    <th class="tg-wa1i" colspan="3">Naturalness</th>
    <th class="tg-wa1i" colspan="2">Transfer Intensity</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">Model</td>
    <td class="tg-wa1i">WMD</td>
    <td class="tg-wa1i">BLEU</td>
    <td class="tg-wa1i">B-P</td>
    <td class="tg-wa1i">B-R</td>
    <td class="tg-wa1i">B-F1</td>
    <td class="tg-wa1i">N-A</td>
    <td class="tg-wa1i">N-C</td>
    <td class="tg-wa1i">N-D</td>
    <td class="tg-wa1i">ACCU</td>
    <td class="tg-wa1i">EMD</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/2102.00769.pdf" target="_blank" rel="noopener noreferrer">GTAE</a>(shi2021gtae)</td>
    <td class="tg-nrix">0.1506</td>
    <td class="tg-nrix">65.61</td>
    <td class="tg-nrix">0.6577</td>
    <td class="tg-nrix">0.6706</td>
    <td class="tg-nrix">0.6640</td>
    <td class="tg-nrix">0.3310</td>
    <td class="tg-nrix">0.7852</td>
    <td class="tg-nrix">0.7318</td>
    <td class="tg-nrix">0.900</td>
    <td class="tg-nrix">0.8990</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="http://papers.nips.cc/paper/7259-style-transfer-from-non-parallel-text-by-cross-alignment.pdf" target="_blank" rel="noopener noreferrer">CAAE</a>(shen2017)</td>
    <td class="tg-nrix">0.4968</td>
    <td class="tg-nrix">15.68</td>
    <td class="tg-nrix">0.3217</td>
    <td class="tg-nrix">0.3240</td>
    <td class="tg-nrix">0.3230</td>
    <td class="tg-nrix">0.2715</td>
    <td class="tg-nrix">0.7052</td>
    <td class="tg-nrix">0.7370</td>
    <td class="tg-nrix">0.828</td>
    <td class="tg-nrix">0.8259</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_DeleteOnly</a>(li2018)</td>
    <td class="tg-nrix">0.5000</td>
    <td class="tg-nrix">30.76</td>
    <td class="tg-nrix">0.3295</td>
    <td class="tg-nrix">0.3932</td>
    <td class="tg-nrix">0.3605</td>
    <td class="tg-nrix">0.3155</td>
    <td class="tg-nrix">0.8534</td>
    <td class="tg-nrix">0.6490</td>
    <td class="tg-nrix">0.958</td>
    <td class="tg-nrix">0.9565</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR</a>(li2018)</td>
    <td class="tg-nrix">0.5109</td>
    <td class="tg-nrix">35.48</td>
    <td class="tg-nrix">0.3352</td>
    <td class="tg-nrix">0.3966</td>
    <td class="tg-nrix">0.3649</td>
    <td class="tg-nrix">0.3190</td>
    <td class="tg-nrix">0.8472</td>
    <td class="tg-nrix">0.7081</td>
    <td class="tg-nrix">0.977</td>
    <td class="tg-nrix">0.9747</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_RetrieveOnly</a>(li2018)</td>
    <td class="tg-nrix">0.7771</td>
    <td class="tg-nrix">10.14</td>
    <td class="tg-nrix">0.1590</td>
    <td class="tg-nrix">0.1840</td>
    <td class="tg-nrix">0.1709</td>
    <td class="tg-nrix">0.3219</td>
    <td class="tg-nrix">0.7854</td>
    <td class="tg-nrix">0.7271</td>
    <td class="tg-nrix">0.998</td>
    <td class="tg-nrix">0.9960</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="http://proceedings.mlr.press/v80/zhao18b/zhao18b.pdf" target="_blank" rel="noopener noreferrer">ARAE</a>(zhao2018)</td>
    <td class="tg-nrix">1.0347</td>
    <td class="tg-nrix">2.95</td>
    <td class="tg-nrix">0.0203</td>
    <td class="tg-nrix">0.0117</td>
    <td class="tg-nrix">0.0158</td>
    <td class="tg-nrix">0.3092</td>
    <td class="tg-nrix">0.7763</td>
    <td class="tg-nrix">0.7333</td>
    <td class="tg-nrix">0.944</td>
    <td class="tg-nrix">0.9412</td>
  </tr>
</tbody>
</table>



##  Paper-news Title Dataset

<table class="tg">
<thead>
  <tr>
    <th class="tg-uzvj">Dataset:&nbsp;&nbsp;&nbsp;Title</th>
    <th class="tg-uzvj" colspan="5">Content Preservation</th>
    <th class="tg-uzvj" colspan="3">Naturalness</th>
    <th class="tg-uzvj" colspan="2">Transfer Intensity</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-uzvj">Model</td>
    <td class="tg-uzvj">WMD</td>
    <td class="tg-uzvj">BLEU</td>
    <td class="tg-uzvj">B-P</td>
    <td class="tg-uzvj">B-R</td>
    <td class="tg-uzvj">B-F1</td>
    <td class="tg-uzvj">N-A</td>
    <td class="tg-uzvj">N-C</td>
    <td class="tg-uzvj">N-D</td>
    <td class="tg-uzvj">ACCU</td>
    <td class="tg-uzvj">EMD</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/2102.00769.pdf" target="_blank" rel="noopener noreferrer">GTAE</a>(shi2021gtae)</td>
    <td class="tg-9wq8">0.5161</td>
    <td class="tg-9wq8">19.67</td>
    <td class="tg-9wq8">0.1923</td>
    <td class="tg-9wq8">0.2134</td>
    <td class="tg-9wq8">0.2034</td>
    <td class="tg-9wq8">0.0949</td>
    <td class="tg-9wq8">0.4181</td>
    <td class="tg-9wq8">0.4567</td>
    <td class="tg-9wq8">0.956</td>
    <td class="tg-9wq8">0.9492</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_DeleteOnly</a>(li2018)</td>
    <td class="tg-9wq8">0.8413</td>
    <td class="tg-9wq8">4.75</td>
    <td class="tg-9wq8">0.0939</td>
    <td class="tg-9wq8">0.0412</td>
    <td class="tg-9wq8">0.0677</td>
    <td class="tg-9wq8">0.3912</td>
    <td class="tg-9wq8">0.8374</td>
    <td class="tg-9wq8">0.4495</td>
    <td class="tg-9wq8">0.881</td>
    <td class="tg-9wq8">0.8687</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR</a>(li2018)</td>
    <td class="tg-9wq8">0.8567</td>
    <td class="tg-9wq8">5.04</td>
    <td class="tg-9wq8">0.0249</td>
    <td class="tg-9wq8">0.0212</td>
    <td class="tg-9wq8">0.0234</td>
    <td class="tg-9wq8">0.2462</td>
    <td class="tg-9wq8">0.7387</td>
    <td class="tg-9wq8">0.4625</td>
    <td class="tg-9wq8">0.933</td>
    <td class="tg-9wq8">0.9234</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="http://papers.nips.cc/paper/7259-style-transfer-from-non-parallel-text-by-cross-alignment.pdf" target="_blank" rel="noopener noreferrer">CAAE</a>(shen2017)</td>
    <td class="tg-9wq8">0.9226</td>
    <td class="tg-9wq8">0.82</td>
    <td class="tg-9wq8">0.0067</td>
    <td class="tg-9wq8">-0.0099</td>
    <td class="tg-9wq8">-0.0008</td>
    <td class="tg-9wq8">0.2167</td>
    <td class="tg-9wq8">0.5627</td>
    <td class="tg-9wq8">0.4422</td>
    <td class="tg-9wq8">0.972</td>
    <td class="tg-9wq8">0.9612</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_RetrieveOnly</a>(li2018)</td>
    <td class="tg-9wq8">0.9842</td>
    <td class="tg-9wq8">0.37</td>
    <td class="tg-9wq8">-0.0383</td>
    <td class="tg-9wq8">-0.0362</td>
    <td class="tg-9wq8">-0.0365</td>
    <td class="tg-9wq8">0.1490</td>
    <td class="tg-9wq8">0.5701</td>
    <td class="tg-9wq8">0.4261</td>
    <td class="tg-9wq8">0.995</td>
    <td class="tg-9wq8">0.9856</td>
  </tr>
  <tr>
    <td class="tg-9wq8"><a href="http://proceedings.mlr.press/v80/zhao18b/zhao18b.pdf" target="_blank" rel="noopener noreferrer">ARAE</a>(zhao2018)</td>
    <td class="tg-9wq8">1.0253</td>
    <td class="tg-9wq8">0.00</td>
    <td class="tg-9wq8">-0.0447</td>
    <td class="tg-9wq8">-0.0539</td>
    <td class="tg-9wq8">-0.0486</td>
    <td class="tg-9wq8">0.2318</td>
    <td class="tg-9wq8">0.6061</td>
    <td class="tg-9wq8">0.4765</td>
    <td class="tg-9wq8">0.989</td>
    <td class="tg-9wq8">0.9782</td>
  </tr>
</tbody>
</table>




## Relevant Citation
```
@article{shi2021gtae,
  title={GTAE: Graph-Transformer based Auto-Encoders for Linguistic-Constrained Text Style Transfer},
  author={Shi, Yukai and Zhang, Sen and Zhou, Chenxing and Liang, Xiaodan and Yang, Xiaojun and Lin, Liang},
  journal={ACM Transactions on Intelligent Systems and Technology},
  year={2021}
}
@article{dai2019,
  title={Style transformer: Unpaired text style transfer without disentangled latent representation},
  author={Dai, Ning and Liang, Jianze and Qiu, Xipeng and Huang, Xuanjing},
  journal={arXiv preprint arXiv:1905.05621},
  year={2019}
}

@article{luo2019,
  title={A dual reinforcement learning framework for unsupervised text style transfer},
  author={Luo, Fuli and Li, Peng and Zhou, Jie and Yang, Pengcheng and Chang, Baobao and Sui, Zhifang and Sun, Xu},
  journal={arXiv preprint arXiv:1905.10060},
  year={2019}
}

@article{zhang2018,
	title="Style Transfer as Unsupervised Machine Translation",
	author="Zhirui {Zhang} and Shuo {Ren} and Shujie {Liu} and Jianyong {Wang} and Peng {Chen} and Mu {Li} and Ming {Zhou} and Enhong {Chen}",
	journal="arXiv preprint arXiv:1808.07894",
	notes="Sourced from Microsoft Academic - https://academic.microsoft.com/paper/2888173624",
	year="2018"
}

@article{xu2018,
	title="Unpaired Sentiment-to-Sentiment Translation: A Cycled Reinforcement Learning Approach",
	author="Jingjing {Xu} and Xu {Sun} and Qi {Zeng} and Xuancheng {Ren} and Xiaodong {Zhang} and Houfeng {Wang} and Wenjie {Li}",
	journal="arXiv preprint arXiv:1805.05181",
	notes="Sourced from Microsoft Academic - https://academic.microsoft.com/paper/2801454967",
	year="2018"
}

@inproceedings{li2018,
	title="Delete, retrieve, generate: A simple approach to sentiment and style transfer",
	author="Juncen {Li} and Robin {Jia} and He {He} and Percy {Liang}",
	booktitle="NAACL HLT 2018: 16th Annual Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
	volume="1",
	pages="1865--1874",
	year="2018"
}

@article{shen2017,
	title="Style transfer from non-parallel text by cross-alignment",
	author="Tianxiao {Shen} and Tao {Lei} and Regina {Barzilay} and Tommi S. {Jaakkola}",
	journal="Neural Information Processing Systems",
	pages="6830--6841",
	year="2017"
}

@article{jin2019,
  title={IMaT: Unsupervised Text Attribute Transfer via Iterative Matching and Translation},
  author={Jin, Zhijing and Jin, Di and Mueller, Jonas and Matthews, Nicholas and Santus, Enrico},
  journal={arXiv preprint arXiv:1901.11333},
  year={2019}
}

@article{fu2018,
	title="Style transfer in text: Exploration and evaluation",
	author="Zhenxin {Fu} and Xiaoye {Tan} and Nanyun {Peng} and Dongyan {Zhao} and Rui {Yan}",
	journal="National Conference on Artificial Intelligence",
	pages="663--670",
	year="2018"
}


@article{prabhumoye2018,
	title="Style transfer through back-translation",
	author="Shrimai {Prabhumoye} and Yulia {Tsvetkov} and Ruslan {Salakhutdinov} and Alan W {Black}",
	journal="Meeting of the Association for Computational Linguistics",
	volume="1",
	pages="866--876",
	year="2018"
}

@inproceedings{zhao2018,
	title="Adversarially regularized autoencoders",
	author="Junbo Jake {Zhao} and Yoon {Kim} and Kelly {Zhang} and Alexander M. {Rush} and Yann {LeCun}",
	booktitle="ICML 2018: Thirty-fifth International Conference on Machine Learning",
	pages="9405--9420",
	year="2018"
}

@article{hu2018,
  title={Texar: A modularized, versatile, and extensible toolkit for text generation},
  author={Hu, Zhiting and Shi, Haoran and Tan, Bowen and Wang, Wentao and Yang, Zichao and Zhao, Tiancheng and He, Junxian and Qin, Lianhui and Wang, Di and Ma, Xuezhe and others},
  journal={arXiv preprint arXiv:1809.00794},
  year={2018}
}

@inproceedings{yang2018,
  title={Unsupervised text style transfer using language models as discriminators},
  author={Yang, Zichao and Hu, Zhiting and Dyer, Chris and Xing, Eric P and Berg-Kirkpatrick, Taylor},
  booktitle={Advances in Neural Information Processing Systems},
  pages={7287--7298},
  year={2018}
}

@article{tian2018,
  title={Structured content preservation for unsupervised text style transfer},
  author={Tian, Youzhi and Hu, Zhiting and Yu, Zhou},
  journal={arXiv preprint arXiv:1810.06526},
  year={2018}
}
```








# Text Style Transfer Benchmark



```HTML
<table class="tg">
<thead>
  <tr>
    <th class="tg-9wq8">Dataset:&nbsp;&nbsp;&nbsp;Yelp</th>
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
  <tr>
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1905.05621" target="_blank" rel="noopener noreferrer">StyleTrans-multi</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1905.10060" target="_blank" rel="noopener noreferrer">DualRL</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1905.05621" target="_blank" rel="noopener noreferrer">StyleTrans-cond</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1808.07894" target="_blank" rel="noopener noreferrer">UnsuperMT</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1805.05181" target="_blank" rel="noopener noreferrer">UnpairedRL</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_Template</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_DeleteOnly</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_DeleteRetrieve</a></td>
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
    <td class="tg-9wq8"><a href="http://papers.nips.cc/paper/7259-style-transfer-from-non-parallel-text-by-cross-alignment.pdf" target="_blank" rel="noopener noreferrer">CAAE</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1901.11333" target="_blank" rel="noopener noreferrer">IMaT</a></td>
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
    <td class="tg-9wq8"><a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPDFInterstitial/17015/15745" target="_blank" rel="noopener noreferrer">Multi_Decoder</a></td>
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
    <td class="tg-9wq8"><a href="https://www.aclweb.org/anthology/P19-1194.pdf" target="_blank" rel="noopener noreferrer">FineGrained-0.7</a></td>
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
    <td class="tg-9wq8"><a href="https://www.aclweb.org/anthology/P19-1194.pdf" target="_blank" rel="noopener noreferrer">FineGrained-0.9</a></td>
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
    <td class="tg-9wq8"><a href="https://www.aclweb.org/anthology/P19-1194.pdf" target="_blank" rel="noopener noreferrer">FineGrained-0.5</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.09000" target="_blank" rel="noopener noreferrer">BackTranslation</a></td>
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
    <td class="tg-9wq8"><a href="https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPDFInterstitial/17015/15745" target="_blank" rel="noopener noreferrer">Style_Emb</a></td>
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
    <td class="tg-9wq8"><a href="https://arxiv.org/pdf/1804.06437" target="_blank" rel="noopener noreferrer">DAR_RetrieveOnly</a></td>
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
    <td class="tg-9wq8"><a href="http://proceedings.mlr.press/v80/zhao18b/zhao18b.pdf" target="_blank" rel="noopener noreferrer">ARAE</a></td>
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
```


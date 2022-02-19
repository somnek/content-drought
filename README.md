# content-drought
<p align="center">
  <img src="https://news.cgtn.com/news/7959544e7a517a4e3067444d34637a4e7863444f31457a6333566d54/img/131fd68c199a439d92436bd943d8b369/131fd68c199a439d92436bd943d8b369.jpg" width="325" title="Manticore">
</p>
<br />

Telegram bot that tells you whos live and shit.

## todo:
- show whos live on category  
- using simple nlp to detect intent  

<details>
  <summary>Click to expand:</summary>
  
```bash
$ manticore examples/evm/umd_example.sol 
 [9921] m.main:INFO: Registered plugins: DetectUninitializedMemory, DetectReentrancySimple, DetectExternalCallAndLeak, ...
 [9921] m.e.manticore:INFO: Starting symbolic create contract
 [9921] m.e.manticore:INFO: Starting symbolic transaction: 0
 [9921] m.e.manticore:INFO: 4 alive states, 6 terminated states
 [9921] m.e.manticore:INFO: Starting symbolic transaction: 1
 [9921] m.e.manticore:INFO: 16 alive states, 22 terminated states
[13761] m.c.manticore:INFO: Generated testcase No. 0 - STOP(3 txs)
[13754] m.c.manticore:INFO: Generated testcase No. 1 - STOP(3 txs)
...
[13743] m.c.manticore:INFO: Generated testcase No. 36 - THROW(3 txs)
[13740] m.c.manticore:INFO: Generated testcase No. 37 - THROW(3 txs)
[9921] m.c.manticore:INFO: Results in ~/manticore/mcore_gsncmlgx
```
</details>

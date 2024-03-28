<!-----



Conversion time: 2.356 seconds.


Using this Markdown file:

1. Paste this output into your source file.
2. See the notes and action items below regarding this conversion run.
3. Check the rendered output (headings, lists, code blocks, tables) for proper
   formatting and use a linkchecker before you publish this page.

Conversion notes:

* Docs to Markdown version 1.0β35
* Thu Mar 28 2024 06:24:52 GMT-0700 (PDT)
* Source doc: ICML more archs
* Tables are currently converted to HTML tables.
----->



## MLP


### Increasing width 


#### Average accuracy - 0 vs 7 - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>Width
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>$${\color{blue}65}$$
   </td>
   <td>$${\color{red}72.9
}$$   </td>
   <td>$${\color{blue}79.7
}$$   </td>
   <td>$${\color{red}90.5
}$$   </td>
   <td>$${\color{blue}85
}$$   </td>
   <td>$${\color{red}94.1
}$$   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>$${\color{blue}64}$$
   </td>
   <td>$${\color{red}77.4
}$$   </td>
   <td>$${\color{blue}78.9
}$$   </td>
   <td>$${\color{red}92.3
}$$   </td>
   <td>$${\color{blue}84.1
}$$   </td>
   <td>$${\color{red}95.4
}$$   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>$${\color{blue}63.9}$$
   </td>
   <td>$${\color{red}84.4
}$$   </td>
   <td>$${\color{blue}78.5
}$$   </td>
   <td>$${\color{red}93.5
}$$   </td>
   <td>$${\color{blue}83.8
}$$   </td>
   <td>$${\color{red}96.3
}$$   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}64.2}$$
   </td>
   <td>$${\color{red}87.2
}$$   </td>
   <td>$${\color{blue}78.3
}$$   </td>
   <td>$${\color{red}94
}$$   </td>
   <td>$${\color{blue}83.6
}$$   </td>
   <td>$${\color{red}96.5
}$$   </td>
  </tr>
</table>



#### Average accuracy - 3 vs 5 - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>width
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>$${\color{blue}54.1}$$
   </td>
   <td>$${\color{red}56.5
}$$   </td>
   <td>$${\color{blue}64
}$$   </td>
   <td>$${\color{red}70.8
}$$   </td>
   <td>$${\color{blue}70.3
}$$   </td>
   <td>$${\color{red}78.5
}$$   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>$${\color{blue}53.1}$$
   </td>
   <td>$${\color{red}58.4
}$$   </td>
   <td>$${\color{blue}63.8
}$$   </td>
   <td>$${\color{red}73
}$$   </td>
   <td>$${\color{blue}69.6
}$$   </td>
   <td>$${\color{red}80.2
}$$   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>$${\color{blue}53.7}$$
   </td>
   <td>$${\color{red}61.3
}$$   </td>
   <td>$${\color{blue}63.5
}$$   </td>
   <td>$${\color{red}74.6
}$$   </td>
   <td>$${\color{blue}69.8
}$$   </td>
   <td>$${\color{red}81.3
}$$   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}53.9}$$
   </td>
   <td>$${\color{red}62.3
}$$   </td>
   <td>$${\color{blue}63.6
}$$   </td>
   <td>$${\color{red}75.3
}$$   </td>
   <td>$${\color{blue}69.5
}$$   </td>
   <td>$${\color{red}81.8
}$$   </td>
  </tr>
</table>



#### Average accuracy - bird vs ship - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>width
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>$${\color{blue}50.95
}$$   </td>
   <td>$${\color{red}52
}$$   </td>
   <td>$${\color{blue}61.5
}$$   </td>
   <td>$${\color{red}71.2
}$$   </td>
   <td>$${\color{blue}64.3* (165)
}$$   </td>
   <td>$${\color{red}74.7
}$$   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>$${\color{blue}50.5
}$$   </td>
   <td>$${\color{red}51.7
}$$   </td>
   <td>$${\color{blue}60.1
}$$   </td>
   <td>$${\color{red}72.8
}$$   </td>
   <td>$${\color{blue}64.1* (112)
}$$   </td>
   <td>$${\color{red}76.1
}$$   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>$${\color{blue}50.6
}$$   </td>
   <td>$${\color{red}51.5
}$$   </td>
   <td>$${\color{blue}60.1
}$$   </td>
   <td>$${\color{red}74.1
}$$   </td>
   <td>$${\color{blue}62.7* (91)
}$$   </td>
   <td>$${\color{red}77
}$$   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}50.6
}$$   </td>
   <td>$${\color{red}50.9
}$$   </td>
   <td>$${\color{blue}59.9
}$$   </td>
   <td>$${\color{red}74.3
}$$   </td>
   <td>$${\color{blue}63* (80)
}$$   </td>
   <td>$${\color{red}77.4
}$$   </td>
  </tr>
</table>



### Increasing depth


#### Average accuracy - 0 vs 7 - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>Hidden layers
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}69
}$$   </td>
   <td>$${\color{red}83.5
}$$   </td>
   <td>$${\color{blue}82.6
}$$   </td>
   <td>$${\color{red}93.97
}$$   </td>
   <td>$${\color{blue}86.9
}$$   </td>
   <td>$${\color{red}96.4
}$$   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>$${\color{blue}67.1
}$$   </td>
   <td>$${\color{red}80.9
}$$   </td>
   <td>$${\color{blue}81.4
}$$   </td>
   <td>$${\color{red}93.5
}$$   </td>
   <td>$${\color{blue}86.2
}$$   </td>
   <td>$${\color{red}96.1
}$$   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>$${\color{blue}65.3
}$$   </td>
   <td>$${\color{red}78.7
}$$   </td>
   <td>$${\color{blue}79.9
}$$   </td>
   <td>$${\color{red}93
}$$   </td>
   <td>$${\color{blue}85.1
}$$   </td>
   <td>$${\color{red}95.7
}$$   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>$${\color{blue}64
}$$   </td>
   <td>$${\color{red}77.4
}$$   </td>
   <td>$${\color{blue}78.9
}$$   </td>
   <td>$${\color{red}92.3
}$$   </td>
   <td>$${\color{blue}84.1
}$$   </td>
   <td>$${\color{red}95.4
}$$   </td>
  </tr>
</table>



#### Average accuracy - 3 vs 5 - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>Hidden layers
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}55
}$$   </td>
   <td>$${\color{red}59.6
}$$   </td>
   <td>$${\color{blue}66.7
}$$   </td>
   <td>$${\color{red}75.4
}$$   </td>
   <td>$${\color{blue}73
}$$   </td>
   <td>$${\color{red}82.5
}$$   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>$${\color{blue}55.3
}$$   </td>
   <td>$${\color{red}58.8
}$$   </td>
   <td>$${\color{blue}65.8
}$$   </td>
   <td>$${\color{red}74.4
}$$   </td>
   <td>$${\color{blue}71.1
}$$   </td>
   <td>$${\color{red}81.6
}$$   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>$${\color{blue}53.7
}$$   </td>
   <td>$${\color{red}58.7
}$$   </td>
   <td>$${\color{blue}64.3
}$$   </td>
   <td>$${\color{red}73.6
}$$   </td>
   <td>$${\color{blue}70.5
}$$   </td>
   <td>$${\color{red}80.6
}$$   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>$${\color{blue}53.1
}$$   </td>
   <td>$${\color{red}58.4
}$$   </td>
   <td>$${\color{blue}63.8
}$$   </td>
   <td>$${\color{red}73
}$$   </td>
   <td>$${\color{blue}69.6
}$$   </td>
   <td>$${\color{red}80.2
}$$   </td>
  </tr>
</table>



#### Average accuracy - bird vs ship - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>Hidden layers
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}50.5
}$$   </td>
   <td>$${\color{red}52.4
}$$   </td>
   <td>$${\color{blue}64.5
}$$   </td>
   <td>$${\color{red}75.1
}$$   </td>
   <td>$${\color{blue}67.2
}$$   </td>
   <td>$${\color{red}77.6
}$$   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>$${\color{blue}50.9
}$$   </td>
   <td>$${\color{red}52
}$$   </td>
   <td>$${\color{blue}62.6
}$$   </td>
   <td>$${\color{red}74.1
}$$   </td>
   <td>$${\color{blue}65.6
}$$   </td>
   <td>$${\color{red}77.1
}$$   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>$${\color{blue}50.4
}$$   </td>
   <td>$${\color{red}51.9
}$$   </td>
   <td>$${\color{blue}61.2
}$$   </td>
   <td>$${\color{red}73.4
}$$   </td>
   <td>$${\color{blue}64.3
}$$   </td>
   <td>$${\color{red}76.4
}$$   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>$${\color{blue}50.5
}$$   </td>
   <td>$${\color{red}51.7
}$$   </td>
   <td>$${\color{blue}60.1
}$$   </td>
   <td>$${\color{red}72.8
}$$   </td>
   <td>$${\color{blue}64.1* (112)
}$$   </td>
   <td>$${\color{red}76.1
}$$   </td>
  </tr>
</table>



## Resnet4


### Increasing width


#### Average accuracy - 0 vs 7 - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>width
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>$${\color{blue}62.5
}$$   </td>
   <td>$${\color{red}75.6
}$$   </td>
   <td>$${\color{blue}80.7
}$$   </td>
   <td>$${\color{red}92.1
}$$   </td>
   <td>$${\color{blue}85.8
}$$   </td>
   <td>$${\color{red}95.2
}$$   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>$${\color{blue}62.9
}$$   </td>
   <td>$${\color{red}84.8
}$$   </td>
   <td>$${\color{blue}80.4
}$$   </td>
   <td>$${\color{red}94.8
}$$   </td>
   <td>$${\color{blue}85.3
}$$   </td>
   <td>$${\color{red}96.8
}$$   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>$${\color{blue}63.6
}$$   </td>
   <td>$${\color{red}91.7
}$$   </td>
   <td>$${\color{blue}79.9
}$$   </td>
   <td>$${\color{red}96.1
}$$   </td>
   <td>$${\color{blue}84.8
}$$   </td>
   <td>$${\color{red}97.7
}$$   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}64.1
}$$   </td>
   <td>$${\color{red}93.2
}$$   </td>
   <td>$${\color{blue}79.9
}$$   </td>
   <td>$${\color{red}96.4
}$$   </td>
   <td>$${\color{blue}84.8
}$$   </td>
   <td>$${\color{red}98.1
}$$   </td>
  </tr>
</table>



#### Average accuracy - 3 vs 5 - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>width
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>$${\color{blue}54.7
}$$   </td>
   <td>$${\color{red}62.9
}$$   </td>
   <td>$${\color{blue}68.3
}$$   </td>
   <td>$${\color{red}78.2
}$$   </td>
   <td>$${\color{blue}74.8
}$$   </td>
   <td>$${\color{red}83.6
}$$   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>$${\color{blue}55.5
}$$   </td>
   <td>$${\color{red}68.8
}$$   </td>
   <td>$${\color{blue}68.2
}$$   </td>
   <td>$${\color{red}82.4
}$$   </td>
   <td>$${\color{blue}75.1
}$$   </td>
   <td>$${\color{red}87
}$$   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>$${\color{blue}55.4
}$$   </td>
   <td>$${\color{red}73.2
}$$   </td>
   <td>$${\color{blue}68.5
}$$   </td>
   <td>$${\color{red}85.3
}$$   </td>
   <td>$${\color{blue}73.8
}$$   </td>
   <td>$${\color{red}89
}$$   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}55.7
}$$   </td>
   <td>$${\color{red}74.7
}$$   </td>
   <td>$${\color{blue}68.5
}$$   </td>
   <td>$${\color{red}86
}$$   </td>
   <td>$${\color{blue}73.3
}$$   </td>
   <td>$${\color{red}89.9
}$$   </td>
  </tr>
</table>



#### Average accuracy - bird vs ship - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>width
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>$${\color{blue}51.3
}$$   </td>
   <td>$${\color{red}53.1
}$$   </td>
   <td>$${\color{blue}59.6
}$$   </td>
   <td>$${\color{red}65.4
}$$   </td>
   <td>$${\color{blue}64.8
}$$   </td>
   <td>$${\color{red}69.2
}$$   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>$${\color{blue}51.2
}$$   </td>
   <td>$${\color{red}54.5
}$$   </td>
   <td>$${\color{blue}60.5
}$$   </td>
   <td>$${\color{red}70.3
}$$   </td>
   <td>$${\color{blue}64.8* (480)
}$$   </td>
   <td>$${\color{red}73.1
}$$   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>$${\color{blue}51.6
}$$   </td>
   <td>$${\color{red}55.8
}$$   </td>
   <td>$${\color{blue}60.7
}$$   </td>
   <td>$${\color{red}74
}$$   </td>
   <td>$${\color{blue}64.8* (252)
}$$   </td>
   <td>$${\color{red}76.3
}$$   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>$${\color{blue}51.2
}$$   </td>
   <td>$${\color{red}57.3
}$$   </td>
   <td>$${\color{blue}61.3
}$$   </td>
   <td>$${\color{red}75.6
}$$   </td>
   <td>$${\color{blue}65* (154)
}$$   </td>
   <td>$${\color{red}77.4
}$$   </td>
  </tr>
</table>



### Increasing depth 


#### Average accuracy - 0 vs 7 - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>ResNet layers
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1 
   </td>
   <td>$${\color{blue}70.8
}$$   </td>
   <td>$${\color{red}94.4
}$$   </td>
   <td>$${\color{blue}84.8
}$$   </td>
   <td>$${\color{red}96.5
}$$   </td>
   <td>$${\color{blue}88.8
}$$   </td>
   <td>$${\color{red}97.8
}$$   </td>
  </tr>
  <tr>
   <td>2 
   </td>
   <td>$${\color{blue}66.7
}$$   </td>
   <td>$${\color{red}90.8
}$$   </td>
   <td>$${\color{blue}81.9
}$$   </td>
   <td>$${\color{red}95.7
}$$   </td>
   <td>$${\color{blue}86.7
}$$   </td>
   <td>$${\color{red}97.3
}$$   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>$${\color{blue}62.9
}$$   </td>
   <td>$${\color{red}84.8
}$$   </td>
   <td>$${\color{blue}80.4
}$$   </td>
   <td>$${\color{red}94.8
}$$   </td>
   <td>$${\color{blue}85.3
}$$   </td>
   <td>$${\color{red}96.8
}$$   </td>
  </tr>
</table>



#### Average accuracy - 3 vs 5 - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>ResNet layers
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1 
   </td>
   <td>$${\color{blue}54.8
}$$   </td>
   <td>$${\color{red}65.6
}$$   </td>
   <td>$${\color{blue}70
}$$   </td>
   <td>$${\color{red}81.8
}$$   </td>
   <td>$${\color{blue}75.2
}$$   </td>
   <td>$${\color{red}85.8
}$$   </td>
  </tr>
  <tr>
   <td>2 
   </td>
   <td>$${\color{blue}55.8
}$$   </td>
   <td>$${\color{red}67.8
}$$   </td>
   <td>$${\color{blue}70
}$$   </td>
   <td>$${\color{red}83.3
}$$   </td>
   <td>$${\color{blue}74.8
}$$   </td>
   <td>$${\color{red}87.3
}$$   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>$${\color{blue}55.5
}$$   </td>
   <td>$${\color{red}68.8
}$$   </td>
   <td>$${\color{blue}68.2
}$$   </td>
   <td>$${\color{red}82.4
}$$   </td>
   <td>$${\color{blue}75.1
}$$   </td>
   <td>$${\color{red}87
}$$   </td>
  </tr>
</table>



#### Average accuracy - bird vs ship - 500 models


<table>
  <tr>
   <td>
   </td>
   <td colspan="2" >4 samples
   </td>
   <td colspan="2" >16 samples
   </td>
   <td colspan="2" >24 samples
   </td>
  </tr>
  <tr>
   <td>ResNet layers
   </td>
   <td>$${\color{blue}\text{G\&C}}$$
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$  
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
   <td>$${\color{blue}\text{G\&C}}$$ 
   </td>
   <td>$${\color{red}\text{SGD}}$$ 
   </td>
  </tr>
  <tr>
   <td>1 
   </td>
   <td>$${\color{blue}52.7
}$$   </td>
   <td>$${\color{red}55.7
}$$   </td>
   <td>$${\color{blue}65.3
}$$   </td>
   <td>$${\color{red}74.2
}$$   </td>
   <td>$${\color{blue}69.5
}$$   </td>
   <td>$${\color{red}76.4
}$$   </td>
  </tr>
  <tr>
   <td>2 
   </td>
   <td>$${\color{blue}51.5
}$$   </td>
   <td>$${\color{red}54.4
}$$   </td>
   <td>$${\color{blue}63.5
}$$   </td>
   <td>$${\color{red}71.8
}$$   </td>
   <td>$${\color{blue}67.9
}$$   </td>
   <td>$${\color{red}75.7
}$$   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>$${\color{blue}51.2
}$$   </td>
   <td>$${\color{red}54.5
}$$   </td>
   <td>$${\color{blue}60.5
}$$   </td>
   <td>$${\color{red}70.3
}$$   </td>
   <td>$${\color{blue}64.8* (480)
}$$   </td>
   <td>$${\color{red}73.1
}$$   </td>
  </tr>
</table>


 ## SGD/GD comparison


### Increasing width


#### Average accuracy - 16 samples - 0 vs 7 - 500 samples


<table>
  <tr>
   <td>width
   </td>
   <td>SGD batch 2 
<p>
60 epochs
   </td>
   <td>SGD batch 8 
<p>
60 epochs
   </td>
   <td>SGD batch 8
<p>
240 epoch
   </td>
   <td>GD 
<p>
60 epochs 
   </td>
   <td>GD 
<p>
480 epochs
   </td>
  </tr>
  <tr>
   <td>⅙*
   </td>
   <td>87.3
   </td>
   <td>82.2
   </td>
   <td>86
   </td>
   <td>80.36
   </td>
   <td>85.52
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>90.7
   </td>
   <td>88.1
   </td>
   <td>90.1
   </td>
   <td>86.11
   </td>
   <td>89.98
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>93.6
   </td>
   <td>93.5
   </td>
   <td>93.6
   </td>
   <td>91.5
   </td>
   <td>93.3
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>95.2
   </td>
   <td>94.27
   </td>
   <td>94.9
   </td>
   <td>93.7
   </td>
   <td>94.9
   </td>
  </tr>
</table>



#### Average accuracy - 16 samples - 3 vs 5 - 500 samples


<table>
  <tr>
   <td>width
   </td>
   <td>SGD batch 2 
<p>
60 epochs
   </td>
   <td>SGD batch 8 
<p>
60 epochs
   </td>
   <td>SGD batch 8
<p>
240 epoch
   </td>
   <td>GD 
<p>
60 epochs 
   </td>
   <td>GD 
<p>
480 epochs
   </td>
  </tr>
  <tr>
   <td>⅙*
   </td>
   <td>70.3
   </td>
   <td>66.7
   </td>
   <td>69.1
   </td>
   <td>66
   </td>
   <td>68.9
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>72.6
   </td>
   <td>69.7
   </td>
   <td>72.1
   </td>
   <td>68.2
   </td>
   <td>71.8
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>76.4
   </td>
   <td>74.4
   </td>
   <td>76
   </td>
   <td>72.9
   </td>
   <td>76
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>78.2
   </td>
   <td>77.2
   </td>
   <td>78.3
   </td>
   <td>76.1
   </td>
   <td>78.3
   </td>
  </tr>
</table>



#### Average accuracy  - 16 samples - Bird vs Ship - 500 samples


<table>
  <tr>
   <td>width
   </td>
   <td>SGD batch 2 
<p>
60 epochs
   </td>
   <td>SGD batch 8 
<p>
60 epochs
   </td>
   <td>SGD batch 8
<p>
240 epoch
   </td>
   <td>GD 
<p>
60 epochs 
   </td>
   <td>GD 
<p>
480 epochs
   </td>
  </tr>
  <tr>
   <td>⅙*
   </td>
   <td>61.6
   </td>
   <td>59.9
   </td>
   <td>60.9
   </td>
   <td>58.68
   </td>
   <td>60.75
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>61.6
   </td>
   <td>60
   </td>
   <td>60.5
   </td>
   <td>58.77
   </td>
   <td>60.12
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>68.9
   </td>
   <td>66.6
   </td>
   <td>67.8
   </td>
   <td>64.94
   </td>
   <td>67.62
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>72.6
   </td>
   <td>70.4
   </td>
   <td>71.2
   </td>
   <td>69.16
   </td>
   <td>70.98
   </td>
  </tr>
</table>



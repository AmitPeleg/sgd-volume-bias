## MLP

The MLP contains five layers with the following number of neurons [120, 60, 30, 12, 2]. Since we want the network to be over-parametrized but remain within a feasible number of parameters, we resized the input images by 2 with a max pooling layer, yielding a network with 101,768 parameters. When changing the depth, we use a network with a width of 2/6 and gradually remove the largest layer, as was done for the LeNet architecture.


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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>65
   </td>
   <td>72.9
   </td>
   <td>79.7
   </td>
   <td>90.5
   </td>
   <td>85
   </td>
   <td>94.1
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>64
   </td>
   <td>77.4
   </td>
   <td>78.9
   </td>
   <td>92.3
   </td>
   <td>84.1
   </td>
   <td>95.4
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>63.9
   </td>
   <td>84.4
   </td>
   <td>78.5
   </td>
   <td>93.5
   </td>
   <td>83.8
   </td>
   <td>96.3
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>64.2
   </td>
   <td>87.2
   </td>
   <td>78.3
   </td>
   <td>94
   </td>
   <td>83.6
   </td>
   <td>96.5
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>54.1
   </td>
   <td>56.5
   </td>
   <td>64
   </td>
   <td>70.8
   </td>
   <td>70.3
   </td>
   <td>78.5
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>53.1
   </td>
   <td>58.4
   </td>
   <td>63.8
   </td>
   <td>73
   </td>
   <td>69.6
   </td>
   <td>80.2
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>53.7
   </td>
   <td>61.3
   </td>
   <td>63.5
   </td>
   <td>74.6
   </td>
   <td>69.8
   </td>
   <td>81.3
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>53.9
   </td>
   <td>62.3
   </td>
   <td>63.6
   </td>
   <td>75.3
   </td>
   <td>69.5
   </td>
   <td>81.8
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>50.95
   </td>
   <td>52
   </td>
   <td>61.5
   </td>
   <td>71.2
   </td>
   <td>64.4* (187)
   </td>
   <td>74.7
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>50.5
   </td>
   <td>51.7
   </td>
   <td>60.1
   </td>
   <td>72.8
   </td>
   <td>64* (133)
   </td>
   <td>76.1
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>50.6
   </td>
   <td>51.5
   </td>
   <td>60.1
   </td>
   <td>74.1
   </td>
   <td>62.8* (110)
   </td>
   <td>77
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>50.6
   </td>
   <td>50.9
   </td>
   <td>59.9
   </td>
   <td>74.3
   </td>
   <td>63.2* (87)
   </td>
   <td>77.4
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>69
   </td>
   <td>83.5
   </td>
   <td>82.6
   </td>
   <td>93.97
   </td>
   <td>86.9
   </td>
   <td>96.4
   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>67.1
   </td>
   <td>80.9
   </td>
   <td>81.4
   </td>
   <td>93.5
   </td>
   <td>86.2
   </td>
   <td>96.1
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>65.3
   </td>
   <td>78.7
   </td>
   <td>79.9
   </td>
   <td>93
   </td>
   <td>85.1
   </td>
   <td>95.7
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>64
   </td>
   <td>77.4
   </td>
   <td>78.9
   </td>
   <td>92.3
   </td>
   <td>84.1
   </td>
   <td>95.4
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>55
   </td>
   <td>59.6
   </td>
   <td>66.7
   </td>
   <td>75.4
   </td>
   <td>73
   </td>
   <td>82.5
   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>55.3
   </td>
   <td>58.8
   </td>
   <td>65.8
   </td>
   <td>74.4
   </td>
   <td>71.1
   </td>
   <td>81.6
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>53.7
   </td>
   <td>58.7
   </td>
   <td>64.3
   </td>
   <td>73.6
   </td>
   <td>70.5
   </td>
   <td>80.6
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>53.1
   </td>
   <td>58.4
   </td>
   <td>63.8
   </td>
   <td>73
   </td>
   <td>69.6
   </td>
   <td>80.2
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>50.5
   </td>
   <td>52.4
   </td>
   <td>64.5
   </td>
   <td>75.1
   </td>
   <td>67.2
   </td>
   <td>77.6
   </td>
  </tr>
  <tr>
   <td>2
   </td>
   <td>50.9
   </td>
   <td>52
   </td>
   <td>62.6
   </td>
   <td>74.1
   </td>
   <td>65.6
   </td>
   <td>77.1
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>50.4
   </td>
   <td>51.9
   </td>
   <td>61.2
   </td>
   <td>73.4
   </td>
   <td>64.3
   </td>
   <td>76.4
   </td>
  </tr>
  <tr>
   <td>4
   </td>
   <td>50.5
   </td>
   <td>51.7
   </td>
   <td>60.1
   </td>
   <td>72.8
   </td>
   <td>64* (133)
   </td>
   <td>76.1
   </td>
  </tr>
</table>



## Resnet4

For the ResNet-based architecture, we followed [How to Train Your ResNet 4: Architecture - Myrtle](https://myrtle.ai/learn/how-to-train-your-resnet-4-architecture/), which trains a custom ResNet architecture in 75 seconds with 94% accuracy. The specific implementation contains three layers, two consist residual blocks. The network contains a total of eight convolutional layers and one linear layer. We reduce the number of channels in each layer such that for width 1 and CIFAR10, the network contains 57,930 learnable parameters (similar to the LeNet).


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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>62.5
   </td>
   <td>75.6
   </td>
   <td>80.7
   </td>
   <td>92.1
   </td>
   <td>85.8
   </td>
   <td>95.2
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>62.9
   </td>
   <td>84.8
   </td>
   <td>80.4
   </td>
   <td>94.8
   </td>
   <td>85.3
   </td>
   <td>96.8
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>63.6
   </td>
   <td>91.7
   </td>
   <td>79.9
   </td>
   <td>96.1
   </td>
   <td>84.8
   </td>
   <td>97.7
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>64.1
   </td>
   <td>93.2
   </td>
   <td>79.9
   </td>
   <td>96.4
   </td>
   <td>84.8
   </td>
   <td>98.1
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>54.7
   </td>
   <td>62.9
   </td>
   <td>68.3
   </td>
   <td>78.2
   </td>
   <td>74.8
   </td>
   <td>83.6
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>55.5
   </td>
   <td>68.8
   </td>
   <td>68.2
   </td>
   <td>82.4
   </td>
   <td>75.1
   </td>
   <td>87
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>55.4
   </td>
   <td>73.2
   </td>
   <td>68.5
   </td>
   <td>85.3
   </td>
   <td>73.8
   </td>
   <td>89
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>55.7
   </td>
   <td>74.7
   </td>
   <td>68.5
   </td>
   <td>86
   </td>
   <td>73.3
   </td>
   <td>89.9
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1/6
   </td>
   <td>51.3
   </td>
   <td>53.1
   </td>
   <td>59.6
   </td>
   <td>65.4
   </td>
   <td>64.8
   </td>
   <td>69.2
   </td>
  </tr>
  <tr>
   <td>2/6
   </td>
   <td>51.2
   </td>
   <td>54.5
   </td>
   <td>60.5
   </td>
   <td>70.3
   </td>
   <td>64.8
   </td>
   <td>73.1
   </td>
  </tr>
  <tr>
   <td>4/6
   </td>
   <td>51.6
   </td>
   <td>55.8
   </td>
   <td>60.7
   </td>
   <td>74
   </td>
   <td>64.8* (265)
   </td>
   <td>76.3
   </td>
  </tr>
  <tr>
   <td>1
   </td>
   <td>51.2
   </td>
   <td>57.3
   </td>
   <td>61.3
   </td>
   <td>75.6
   </td>
   <td>65.1* (166)
   </td>
   <td>77.4
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1 
   </td>
   <td>70.8
   </td>
   <td>94.4
   </td>
   <td>84.8
   </td>
   <td>96.5
   </td>
   <td>88.8
   </td>
   <td>97.8
   </td>
  </tr>
  <tr>
   <td>2 
   </td>
   <td>66.7
   </td>
   <td>90.8
   </td>
   <td>81.9
   </td>
   <td>95.7
   </td>
   <td>86.7
   </td>
   <td>97.3
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>62.9
   </td>
   <td>84.8
   </td>
   <td>80.4
   </td>
   <td>94.8
   </td>
   <td>85.3
   </td>
   <td>96.8
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1 
   </td>
   <td>54.8
   </td>
   <td>65.6
   </td>
   <td>70
   </td>
   <td>81.8
   </td>
   <td>75.2
   </td>
   <td>85.8
   </td>
  </tr>
  <tr>
   <td>2 
   </td>
   <td>55.8
   </td>
   <td>67.8
   </td>
   <td>70
   </td>
   <td>83.3
   </td>
   <td>74.8
   </td>
   <td>87.3
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>55.5
   </td>
   <td>68.8
   </td>
   <td>68.2
   </td>
   <td>82.4
   </td>
   <td>75.1
   </td>
   <td>87
   </td>
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
   <td>G&C
   </td>
   <td>SGD 
   </td>
   <td>G&C  
   </td>
   <td>SGD 
   </td>
   <td>G&C 
   </td>
   <td>SGD 
   </td>
  </tr>
  <tr>
   <td>1 
   </td>
   <td>52.7
   </td>
   <td>55.7
   </td>
   <td>65.3
   </td>
   <td>74.2
   </td>
   <td>69.5
   </td>
   <td>76.4
   </td>
  </tr>
  <tr>
   <td>2 
   </td>
   <td>51.5
   </td>
   <td>54.4
   </td>
   <td>63.5
   </td>
   <td>71.8
   </td>
   <td>67.9
   </td>
   <td>75.7
   </td>
  </tr>
  <tr>
   <td>3
   </td>
   <td>51.2
   </td>
   <td>54.5
   </td>
   <td>60.5
   </td>
   <td>70.3
   </td>
   <td>64.8
   </td>
   <td>73.1
   </td>
  </tr>
</table>


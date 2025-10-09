# **Metric-Depth-Distance-Estimation-ONNX**
 - Convert the SOTA depth models into ONNX format.
 - 將SOTA深度模型轉換為ONNX格式。
## **支持的模型 Supported Models**
1. [Depth-Anything-V2](https://github.com/DepthAnything/Depth-Anything-V2)
2. [MoGe-v2](https://github.com/microsoft/MoGe)


### **性能 Performance**  
| OS           | Device       | Backend           | Model        | Time Cost in Seconds <br> (720 x 1280 pixels) |
|:------------:|:------------:|:-----------------:|:------------:|:------------------------------------------------:|
| Ubuntu-24.04 | Desktop      | CPU <br> i7-1165G7 | MoGe-v2-vits <br> f32 | 3.4                                    |
| Ubuntu-24.04 | Desktop      | GPU <br> MX150 | MoGe-v2-vits <br> f32 | 1.5                                        |

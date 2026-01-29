# CloDS: Visual-Only Unsupervised Cloth Dynamics Learning in Unknown Conditions
## 1. Visualization of the learned dynamics (Visuallization of Figure 5)
<table>
  <tr>
    <td align="center">
      <img src="video_show/GT.gif" width="400"><br>
      <strong>Ground Truth</strong>
    </td>
    <td align="center">
      <img src="video_show/CloDS.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td align="center">
      <img src="video_show/GT_mesh.gif" width="400"><br>
      <strong>Ground Truth Mesh</strong>
    </td>
    <td align="center">
      <img src="video_show/CloDS_mesh.gif" width="400"><br>
      <strong>CloDS Mesh (ours)</strong>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td align="center">
      <img src="video_show/TAU.gif" width="400"><br>
      <strong>TAU</strong>
    </td>
    <td align="center">
      <img src="video_show/MMVP.gif" width="400"><br>
      <strong>MMVP</strong>
  </tr>
</table>
<table>
  <tr>
    <td align="center">
      <img src="video_show/gSTA.gif" width="400"><br>
      <strong>SimVP (gSTA)</strong>
    </td>
    <td align="center">
      <img src="video_show/IncepU.gif" width="400"><br>
      <strong>SimVP (IncepU)</strong>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td align="center">
      <img src="video_show/MAU.gif" width="400"><br>
      <strong>MAU</strong>
    </td>
  </tr>
</table>

## 2. Visualization of the ablation studies in SMGS (Visualization of Figure 3)
<table>
  <tr>
    <td align="center">
      <img src="SMGS/GT.gif" width="400"><br>
      <strong>Ground Truth</strong>
    </td>
    <td align="center">
      <img src="SMGS/CloDS.gif" width="400"><br>
      <strong>SMGS (ours)</strong>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td align="center">
      <img src="SMGS/wo_world.gif" width="400"><br>
      <strong> GaMes (w/o $\mu^W$)</strong>
    </td>
    <td align="center">
      <img src="SMGS/wo_mesh.gif" width="400"><br>
      <strong>w/o mesh (w/o $\mu^M$)</strong>
    </td>
  </tr>
</table>

## 3. Generalization to Shape (Visualization of Figure 6a)
<table>
  <tr>
    <td align="center">
      <img src="new_shape/GT.gif" width="400"><br>
      <strong> Ground Truth </strong>
    </td>
    <td align="center">
      <img src="new_shape/CloDS.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>

## 4. Generalization Texture (Visualization of Figure 6b)
<table>
  <tr>
    <td align="center">
      <img src="new_color/GT.gif" width="400"><br>
      <strong> Ground Truth </strong>
    </td>
    <td align="center">
      <img src="new_color/CloDS.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>

## 5. Real-world Experiments (Visualization of Figure 6c)
<table>
  <tr>
    <td align="center">
      <img src="real_loop/real.gif" width="400"><br>
      <strong> Ground Truth </strong>
    </td>
    <td align="center">
      <img src="real_loop/GT.gif" width="400"><br>
      <strong>Ground Truth (SAM)</strong>
    </td>
      <td align="center">
      <img src="real_loop/CloDS.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>

## 6. Performance under Lighting Conditions (Visualization of Figure S.3 in Appendix H.5)
<table>
  <tr>
    <td align="center">
      <img src="mesh/GT_image.gif" width="400"><br>
      <strong>Reference (Rended)</strong>
    </td>
    <td align="center">
      <img src="mesh/GT_mesh.gif" width="400"><br>
      <strong>Reference (Mesh)</strong>
    </td>
    <td align="center">
      <img src="mesh/CloDS.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>

## 7. The result of sora (Visualization of Appendix H.8)
<table>
  <tr>
    <td align="center">
      <img src="sora/sora.gif" width="400"><br>
      <strong>The result of sora. Prompt: 'A flag fluttering in the wind'.</strong>
    </td>
    <td align="center">
      <img src="video_show/CloDS.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>


## 8. Visualization of geometry-aware approaches. (Figure 9a, Reviewer FVhY)
<table>
  <tr>
    <td align="center">
      <img src="image/aware3d/GT_video_26.gif" width="400"><br>
      <strong>Ground Truth</strong>
    </td>
    <td align="center">
      <img src="image/aware3d/node_video_26.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">
      <img src="image/aware3d/node_video_cs_26.gif" width="400"><br>
      <strong>CS</strong>
    </td>
    <td align="center">
      <img src="image/aware3d/node_video_lip_26.gif" width="400"><br>
      <strong>LIP</strong>
    </td>
  </tr>
</table>

## 9. Visualization of object-cloth collision. (Figure 9b, Reviewer bT4z)

<table>
  <tr>
    <td align="center">
      <img src="image/collision/gt.gif" width="400"><br>
      <strong>Ground Truth</strong>
    </td>
    <td align="center">
      <img src="image/collision/pre.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>


## 10. Visualization of Real-world garmen. (Figure 9c, Reviewer kW74 and FVhY)
### 10.1 Pants
<table>
  <tr>
    <td align="center">
      <img src="image//pants/gt.gif" width="400"><br>
      <strong>Ground Truth</strong>
    </td>
    <td align="center">
      <img src="image//pants/pre.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>

### 10.2 Dress
<table>
  <tr>
    <td align="center">
      <img src="image//dress/gt.gif" width="400"><br>
      <strong>Ground Truth</strong>
    </td>
    <td align="center">
      <img src="image//dress/pre.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>

## 11. Visualization of CDR under different noise conditions. (Figure S.2 in Appendix E, Reviewer FVhY)
<table>
  <tr>
    <td align="center">
      <img src="image/noise/GT_video_26.gif" width="400"><br>
      <strong>Ground Truth</strong>
    </td>
    <td align="center">
      <img src="image/noise/pre_video_26.gif" width="400"><br>
      <strong>CloDS (ours)</strong>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">
      <img src="image/noise/gaussian_noise.gif" width="400"><br>
      <strong>Gaussian noise</strong>
    </td>
    <td align="center">
      <img src="image/noise/trans_noise.gif" width="400"><br>
      <strong>Translation noise</strong>
    </td>
  </tr>
</table>
<table>
  <tr>
    <td align="center">
      <img src="image/noise/scale_noise.gif" width="400"><br>
      <strong>Scaling noise</strong>
    </td>
  </tr>
</table>

## 12. Visualization of Extracted mesh. (Figure S.5 in Appendix H.4, Reviewer FVhY)

<table>
  <tr>
    <td align="center">
      <img src="image/extraction/GT_video_32.gif" width="400"><br>
      <strong>Ground Truth Mesh</strong>
    </td>
    <td align="center">
      <img src="image/extraction/Extracted_CloDS_video_32 .gif" width="400"><br>
      <strong>Extracted Mesh (CloDS)</strong>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td align="center">
      <img src="image/extraction/Pre_CloDS_video_32.gif" width="400"><br>
      <strong>Predicted Mesh (CloDS)</strong>
    </td>
    <td align="center">
      <img src="image/extraction/Extracted_wo_video_32.gif" width="400"><br>
      <strong>Extracted Mesh (w/o $\mathcal{L}_{edge}$)</strong>
    </td>
  </tr>
</table>





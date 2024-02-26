---
{"dg-publish":true,"permalink":"/1-area/10-paper-review/101-yolo/1011-you-only-look-once/yolo-v1-combining-fast-r-cnn-and-yolo/","tags":["PaperReview","Study/PaperReview/2D_Detection/YOLO/v1"]}
---





> [!Highlight]
> <mark class="customZot-Blue ">By using YOLO to eliminate background detections from Fast R-CNN we get a significant boost in performance.</mark> ([6](zotero://open-pdf/library/items/VXGPLSWI?page=6&annotation=9RKYVFXU))
>  
 
> [!Highlight]
> <mark class="customZot-Yellow ">For every bounding box that R-CNN predicts we check to see if YOLO predicts a similar box. If it does, we give that prediction a boost based on the probability predicted by YOLO and the overlap between the two boxes.</mark> ([6](zotero://open-pdf/library/items/VXGPLSWI?page=6&annotation=NSG77RHR))
>  
> **Comment**:
> 
> RCNN에서 예측된 박스와 YOLO에서 예측된 박스가 비슷할 경우 겹침도에 따라 해당 예측에 가중치 부여
YOLO: 빠른 처리 속도, background error 낮음
Fast RCNN: 높은 정확도, background error 높음 
  
> [!Image]
> <mark class="customZot-Yellow "> Image</mark>
> ![2_Resource/20_Zotero/201_Literature Notes/@RedmonEtAl2016a/image-6-x306-y78.png](/img/user/2_Resource/20_Zotero/201_Literature%20Notes/@RedmonEtAl2016a/image-6-x306-y78.png) 
> 
  
> [!Image]
> <mark class="customZot-Yellow "> Image</mark>
> ![2_Resource/20_Zotero/201_Literature Notes/@RedmonEtAl2016a/image-7-x43-y494.png](/img/user/2_Resource/20_Zotero/201_Literature%20Notes/@RedmonEtAl2016a/image-7-x43-y494.png) 
> 
 
> [!Highlight]
> <mark class="customZot-Blue ">since YOLO is so fast it doesn’t add any significant computational time compared to Fast R-CNN.</mark> ([7](zotero://open-pdf/library/items/VXGPLSWI?page=7&annotation=YYRQK4W4))
>  
 
# bbox_classification
根据bbox大小、方向、内容是否有效，将标注的bbox分类。

select_unvalid.py : 将bbox label划分为无效文本、长文本、垂直文本、正常文本四类，并做分别储存。

save_bbox.py : 根据normal_bbox.txt，把文本行从全图中crop出来，保存在title文件夹中，并生成title_label.txt文件。

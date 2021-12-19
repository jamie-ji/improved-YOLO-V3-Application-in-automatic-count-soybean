@copyright allrights reserved
受中国知识产权保护
author：Jamie JI
NJAU


使用说明：

开发文档：
使用手册：



#程序结构：

└── software
    ├── build
    │   └── main
    |
    ├──cfg
    |   └──hyp.yaml
    |
    ├──data
    |   ├──Annotations
    |   |
    |   ├──images
    |   |
    |   ├──ImageSets
    |   |       └──Main
    |   |           ├──test.txt
    |   |           ├──train.txt
    |   |           ├──trainval.txt
    |   |           └──val.txt
    |   |
    |   ├──coco.yaml
    |   ├──coco128.yaml
    |   ├──hyp.finetune.yaml
    |   ├──hyp.scratch.yaml
    |   └──voc.yaml
    |
    ├──images
    |
    ├──models
    |    ├──__init__.py
    |    ├──common.py
    |    ├──experimental.py
    |    ├──export.py
    |    └──yolo.py
    |
    ├──newyolo
    |     ├──utils
    |     |    └──autoanchor.py
    |     └──hubconf.py
    |
    ├──runs
    |    └──detect
    |
    ├──utils
    |    ├──__init__.py
    |    ├──activations.py
    |    ├──autoanchor.py
    |    ├──datasets.py
    |    ├──general.py
    |    ├──google_utils.py
    |    ├──metrics.py
    |    ├──plots.py
    |    └──torch_utils.py
    |
    ├──venv
    |
    ├──weights
    |    ├──YOLOV+CIOU+Repulsion.pt
    |    ├──YOLOV3+CIOU.pt
    |    └──yolov5.pt
    |
    ├──detect.py
    ├──Dockerfile
    ├──findpsw_class.py
    ├──findpsw_GUI.py
    ├──globalvar.py
    ├──hubconf.py
    ├──imgstitch_class.py
    ├──imgstitch_GUI.py
    ├──login_GUI.py
    ├──main.py
    ├──makeTxt.py
    ├──mulqrcode.py
    ├──newindex_class.py
    ├──newindex_GUI.py
    ├──Qrcode_excel_class.py
    ├──Qrcode_excel_GUI.py
    ├──Qrcode.py
    ├──select_situation_class.py
    ├──select_situation_GUI.py
    ├──signin_class.py
    ├──signin_GUI.py
    ├──test.py
    ├──train.py
    ├──voc_label.py
    ├──weathe_data.py
    ├──Readme.txt
    └──requirements.txt

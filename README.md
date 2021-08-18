# great_src21_converse

开发集路径：/nvme/zhiyong/voxsrc21_voxconverse

`Use API.ipynb` 中包含最基本的VAD+基于聚类的说话人日志算法和输出流程

VoxSRC2021路径下是官方给的开发集标签和打分脚本

train_dist是直接从GREAT_ASV_system工程中复制过来的说话人特征核心代码

打分方式（使用voxconverse开发集）

`python compute_diarisation_metrics.py -r voxconverse/dev/*.rttm -s /workspace/Voxsrc2021/out.rttm`

结果要求上传.rttm文件

打分系统（ 一共只能上传5次！！！🤣 ）：
>https://competitions.codalab.org/competitions/34113#learn_the_details-evaluation

说话人日志参考资料：
>https://github.com/wq2012/awesome-diarization

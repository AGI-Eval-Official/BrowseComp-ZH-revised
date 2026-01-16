# BrowseComp-ZH-revised

When using the official [BrowseComp-ZH](https://github.com/PALIN2018/BrowseComp-ZH) benchmark, we identified 24 problems with incorrect or inappropriate answers, likely due to changes in time or entities, which may compromise fair comparisons between search agents.

We have manually corrected the answers for 24 problems. `answer` and `raw_answer` correspond to the corrected and original answers, respectively. We provide the specific reasons for the corrections in the `reason` field and use `answer_diff` to identify the modified data. 

The revised benchmark is `./benchmarks/browsecomp-zh.jsonl`, the following is a demo:
```json
{
    "problem": "某歌手出生于中国北方，20岁开始音乐创作，28岁推出第3张个人专辑，专辑名5个字，且带数字。2015年前后，为某音乐综艺冠军担当编曲及制作，第二年为某电影制作的同名主题曲发布。问他举办婚礼的日期",
    "raw_answer": "金志文",
    "answer": "2012/11/23",
    "fix_reason": "Q问题是婚礼日期，原答案为举办婚礼的人",
    "answer_diff": true
}
```

## Contributors & Citation

🎉 We would like to thank the following people for their contributions to the revisions of BrowseComp-ZH, listed alphabetically by last name.

**Contributors:** Yuxin Bian, Xuezhi Cao, Xiaolong Chen, Yan Chen, Shijun Dai, Yuchuan Dai, Qiyuan Duan, Lingchuan Liu, Wei Liu, Xiangyuan Liu, Hongzhi Ni, Lin Qiu, Ziwen Wang, Haoxing Wen, Quanchi Weng, Yue Xu, Chenhui Yang, Hao Yang, Fengcheng Yuan, Jiacheng Zhang, Pengtao Zhang, Rongzhi Zhang, Jiarui Zhao, Peng Zhao, Mingyang Zhu

**If you use the resources from this project, please cite as follows:**

```bibtex
@misc{revisedbench2026,
  author       = {AGI-Eval},
  title        = {BrowseComp-ZH-revised},
  year         = {2026},
  url          = {https://github.com/AGI-Eval-Official/BrowseComp-ZH-revised}
}
```


## ☁️ Contact

If you have any questions, please contact us via:

Email: zhumingyang09@meituan.com, liuwei304@meituan.com


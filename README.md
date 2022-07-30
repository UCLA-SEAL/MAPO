# Mako
Mako: A Low-Pause, High-Throughput Evacuating Collector for Memory-Disaggregated Datacenters (PLDI 2022)

## Summary of Semeru  
Mako is a low-pause, high-throughput garbage collector designed for memory-disaggregated datacenters. Key to Mako’s success is its ability to offload both tracing and evacuation onto memory servers and run these tasks concurrently when the CPU server executes mutator threads. Mako achieves ~12ms at the 90th-percentile pause time and outperforms Shenandoah by an average of 3 times in throughput.

## Team 
This project is done in collaboration with Professor [Harry Xu](http://web.cs.ucla.edu/~harryxu/)'s group at UCLA. Please visit [Mako project at UCLA Systems](https://github.com/uclasystem/Mako). If you encounter any problems, please open an issue or feel free to contact us:

[Haoran Ma](http://www.haoranma.info/): PhD student, [haoranma@ucla.edu](mailto:haoranma@ucla.edu).
Shi Liu: PhD student, [shiliu@g.ucla.edu ](mailto:shiliu@g.ucla.edu );

## How to cite 
Please refer to our PLDI'22 paper, **[Mako: A Low-Pause, High-Throughput Evacuating Collector for Memory-Disaggregated Datacenters](https://dl.acm.org/doi/10.1145/3519939.3523441)** for more details. 

### Bibtex  
```txt
@inproceedings{ma2022mako,
  title={Mako: a low-pause, high-throughput evacuating collector for memory-disaggregated datacenters},
  author={Ma, Haoran and Liu, Shi and Wang, Chenxi and Qiao, Yifan and Bond, Michael D and Blackburn, Stephen M and Kim, Miryung and Xu, Guoqing Harry},
  booktitle={Proceedings of the 43rd ACM SIGPLAN International Conference on Programming Language Design and Implementation},
  pages={92--107},
  year={2022}
}
```


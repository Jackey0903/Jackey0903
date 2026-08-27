<div align="center">

# Haojie Hu · 胡浩杰

**AI Explorer · Software Engineering Undergraduate at Tongji University**

I study how AI systems listen, look, reason, and revise — and I build tools that make those decisions easier to inspect.

[Website](https://jackey0903.github.io/) · [Email](mailto:3038115521@qq.com) · [Tongji University](https://www.tongji.edu.cn/)

</div>

---

## What I am exploring

- **Multimodal perception:** grounding objects and events across audio, vision, motion, and language.
- **Reasoning behavior:** understanding when longer reasoning helps a model and when it only creates drift.
- **AI for research:** inspectable agent workflows for reading, experimentation, and scientific communication.

## Papers

### [PosterMELD: Multi-Agent Paper-to-Poster Generation for Controllable Design Diversity with Editable Print-Ready Outputs](https://arxiv.org/abs/2608.02218)

**Haojie Hu**, Chenhao Dang, Yaojia Liu, Hengrui Kang, Conghui He, Weijia Li
*arXiv:2608.02218* · [Paper](https://arxiv.org/abs/2608.02218) · [Code](https://github.com/Jackey0903/PosterMELD) · [Project page](https://jackey0903.github.io/PosterMELD/)

Turns scientific papers into editable PowerPoint posters through capacity-aware slots, explicit design controls, and bounded visual-quality repair. Evaluated on 621 papers with an 81.3% print-ready rate at roughly $0.38 per poster.

### [Listening to the Motion: Audio-Conditioned Kinematic Verification for Robust Audio-Visual Segmentation](https://github.com/Jackey0903/SKA-VCT)

*Under review* · [Code](https://github.com/Jackey0903/SKA-VCT)

Audio-visual segmentation leans on static visual saliency, so a silent guitar on a poster can outvote the one actually being played. **KEVA** makes audio interrogate the motion field before it is allowed to drive segmentation. On AVSBench it reaches 87.42 / 73.50 / 51.98 mIoU on S4 / MS3 / AVSS, and under deceptive visual saliency its degradation is 3.27 points versus 10.90 for the vision-centric baseline.

### [To Think or Not to Think: Pre-Decisional Reasoning Budgets for Referring Audio-Visual Segmentation](https://github.com/Jackey0903/To-Think-or-Not-to-Think)

*Under review* · [Code](https://github.com/Jackey0903/To-Think-or-Not-to-Think)

Longer chain-of-thought is not uniformly better — forcing it on simple queries is an *overthinking trap*. The hidden state a model holds just before its first reasoning token already predicts, at 70.1% accuracy, whether reasoning will help. Routing on that signal retains ~96% of always-long quality while cutting reasoning tokens by 60%, and transfers zero-shot to out-of-distribution splits.

## Projects

### [DraftCode: NBA Draft War Room](https://github.com/Jackey0903/draftcode)

An auditable NBA draft prediction agent that fuses talent, expert mocks, and market signals across 30 GM personas and 1,500 Monte Carlo scenarios. Built for the AWS Summit Shanghai 2026 hackathon; placed third and advanced to the Macau round.

### [VoxSprite](https://github.com/Jackey0903/VoxSprite)

Turns any voice into a playable instrument with Web Audio, an ESP32-S3, physical keys, and reactive LEDs.

### [Stardew-Valley](https://github.com/Jackey0903/Stardew-Valley)

A Cocos2d-x systems project covering map interaction, character control, collision detection, inventory, and farming simulation mechanics.

## Honors

- **Third Place**, AWS Summit Shanghai Hackathon 2026 — advanced to the Macau round with DraftCode.

## Now

> Looking for AI research and engineering internships around multimodal learning, LLM reasoning, research agents, and evaluation-heavy systems.

Python · PyTorch · C++ · TypeScript · Computer Vision · Multimodal Learning · Multi-Agent Systems · Research Tooling

I also enjoy playful systems, game mechanics, and projects that make difficult ideas visible.

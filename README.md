# SketchESC
Free-hand sketches are appealing for humans as a universal tool to depict the visual world. Humans can recognize varied sketches of a category easily by identifying the concurrence and layout of the intrinsic semantic components of the category, since humans draw free-hand sketches based a common consensus that which types of semantic components constitute each sketch category. For example, an airplane should at least have a fuselage and wings. Based on this analysis, a semantic component-level memory module is constructed and embedded in the proposed structured sketch recognition network in this paper. The memory keys representing semantic components of each sketch category can be self-learned and enhance the recognition network’s explainability. Our proposed networks can deal with different situations of sketch recognition, i.e., with or without semantic components labels of strokes. Experiments on the SPG and SketchIME datasets demonstrate the memory module’s flexibility and the recognition network’s explainability.
![Frame of the Structured Sketch Recognition network](https://note.youdao.com/yws/api/personal/file/WEB9d65247d598695ceb0fddf6276c24e56?method=download&shareKey=91426ee641ce0c3f2d31f5fd99ddc99c)

## Instructions

### Dependencies

torch 1.12.0

torch-geometric 1.6.0

### Dateset

[download](https://drive.google.com/file/d/1R2zOrv5hIv2GOsEwTCZBHLfXcum9j9Ua/view?usp=sharing) SPG dataset to data dir

[download](https://drive.google.com/file/d/1TbaK46IQvI6MCs0JpCcB1Fcx8Nr3i8g8/view?usp=sharing) SketchIME dataset to data dir

[download](https://drive.google.com/file/d/1Mx3zRbZCTDyAUg7S8HSel1v0qJHjRvAX/view?usp=sharing) pretrained transformer model to pretrained_model dir

### Run

``` python main.py ```


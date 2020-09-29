

### Git Tips:
```tips
git branch -a                             // Show all branches (include remote branches)

git checkout -b gh-pages origin/gh-pages  // Pull remote branch to local
git branch -d branch_name                 // Delete one branch

git push origin gh-pages:gh-pages         // Push local gh-pages branch to remote gh-pages branch

git add  /  git commit  /  git
```


### Keras Tips:

- model.add(Dense(32, input_shape=(784,))) 等价于 model.add(Dense(32, input_dim=784))

- 将标签转换为分类的 one-hot 编码:
```
labels = np.random.randint(10, size=(1000, 1))

one_hot_labels = keras.utils.to_categorical(labels, num_classes=10)
```

### Blog Links 
- [Task1](https://summer-qing.github.io/keras/task1.html) [Task2](https://summer-qing.github.io/keras/task2.html)
- [Keras Tutorial](https://summer-qing.github.io/keras/Keras_0.html)
- [keras-mnist-cnn](https://summer-qing.github.io/keras/keras-mnist-cnn.html)

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Summer-Qing/Summer-Qing/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.


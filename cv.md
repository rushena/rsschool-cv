
# Rushen Adjigeldieva
Web-developer

<div id="webaddress">
<a href="mailto:rushena2706@gmail.com">rushena2706@gmail.com</a>
| <a href="https://t.me/rushenka94">Telegram</a>
</div>


## About ME

I have been working in the company for 7 years.  
She has earned the trust of the management for the quality of her work.  
I switched from working with clients to working on the development of internal projects.  
Qualities that managers value: professionalism, ability to work in stressful situations, understanding, responsiveness, ability to set priorities.

## Skills

- HTML5
- CSS
- JavaScript
- React
- NodeJS
- Webpack

## Code Example

``` 
class Node {  
    constructor(value, left = null, right = null){
        this.value = value;
        this.left = left;
        this.right = right;
    }
}

const isBST = node => {

    const fn = (tree) => {
        if (!tree) return [];
        return [...fn(tree.left), tree.value, ...fn(tree.right)]
    }

    const b = fn(node);

    let res = true;

    const x = b[0] > b[1] ? '<' : '>'

    for(let i = 1; i < b.length; i++) {
        const a = x == '<' ? b[i] > b[i - 1] : b[i] < b[i - 1]
        if (a) {
            res = false;
            break;
        }
    }

    return res;
};
```

## Education

- Hexlet Course
- GeekBrains. Programming basics

## English

Level: A
---
slug: mdx
title: Powered by MDX
id: 3-mdx
sidebar_label: Powered by MDX
sidebar_position: "4"

---
You can write JSX and use React components within your Markdown thanks to [MDX](https://mdxjs.com/).

asdjja sdja sdj jasjdjasjdj jasd a 

![](https://4.bp.blogspot.com/-JUIoS9LkTbQ/UpibsLWSooI/AAAAAAAAADU/AMhSsQguhRI/s400/situ-gunung-sukabumi.jpg)

export const Highlight = ({children, color}) => ( <span style={{
backgroundColor: color,
borderRadius: '2px',
color: '#fff',
padding: '0.2rem',
}}>{children}</span> );

<Highlight color="#25c2a0">Docusaurus green</Highlight> and <Highlight color="#1877F2">Facebook blue</Highlight> are my favorite colors.

I can write **Markdown** alongside my _JSX_!
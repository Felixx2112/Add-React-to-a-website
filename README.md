## [React](https://reactjs.org/)

`React a JavaScript library for building user interfaces`

`React là thư viện Javascript dùng để xây dưng giao diện người dùng`

## [Add React to a Website](https://reactjs.org/docs/add-react-to-a-website.html)

```bash
#Add the Script Tags
<script src="https://unpkg.com/react@17/umd/react.development.js" crossorigin></script>
```

## React.createElement()

`React.createElement() sẽ trả về một đối tượng gọi là React element`

`React.createElement(type, props, children, n)`

```bash
      const h1React = React.createElement(
        "h1",
        {
          title: "Hello",
          className: "heading",
        },
        "Hello guys"
      );
      console.log(h1React);
```

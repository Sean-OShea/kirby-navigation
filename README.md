# Kirby Navigation Field (Still in Development)
A Navigation field for Kirby CMS [Kirby CMS](https://getkirby.com),

## Preview
![](https://github.com/chrisbeluga/kirby-navigation/blob/main/navigation-demo-1.png)
![](https://github.com/chrisbeluga/kirby-navigation/blob/main/navigation-demo-2.png)
![](https://github.com/chrisbeluga/kirby-navigation/blob/main/navigation-demo-3.png)

## Installation & Usage
Copy plugin files to your plugin's directory. Use the following blueprint  anywhere you want the navigation to appear

```
 navigation:
   label: Navigation
   type: navigation
   levels: 5
   help: Description of menu or where it is used
   width: 1/2
```

## Info
Nesting limit is set as default to 5, to allow further levels adjust the levels option in the blueprint

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

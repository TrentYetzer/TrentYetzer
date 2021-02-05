
# Hello, I'm Trent Yetzer! 

I currently am studying **CS @ North Dakota State University** from home near **Minneapolis**, and I expect to graduate Spring 2022 with a MS degree. Additionally, I have plans to work as a **SDE Intern @ C.H. Robinson** this coming summer. My hobbies include reading about current **Tech** trends, **Wikipediaing**, **Cooking**, **Video Games**, and **Anime**.  As a software developer, my favorite languages are **TypeScript**, **Java**, **Python**, and **Go** as of recently. Please feel free to look at my portfolio ~~http://trentyetzer.me/~~.

```TypeScript
class README extends React.Component {
	constructor(props) {
		super(props);
		this.state = {
			name: "Trent Yetzer",
			location: "Minneapolis",
			url: "http://trentyetzer.me/",
			school: "CS @ North Dakota State University",
			work: "SDE Intern @ C.H. Robinson",
			hobbies: ["Tech", "Wikipediaing", "Cooking", "Video Games", "Anime"],
			favLanguages: ["TypeScript", "Java", "Python", "Go"],
		};
	}
	componentDidMount() {
		console.log("Introduction complete");
	}
	render() {
		return (
			<h1>Hello, I'm {this.state.name}!</h1>
			<hr />
			<p>
				I currently am studying <strong>{this.state.school}</strong> from home near
				<strong>{this.state.location}</strong>, and I expect to graduate Spring 2022 
				with a MS degree. Additionally, I have plans to work as a <strong>
				{this.state.work}</strong> this coming summer. My hobbies include reading 
				about current <strong>{this.state.hobbies[0]}</strong> trends,
				<strong>{this.state.hobbies[1]}</strong>, <strong>{this.state.hobbies[2]}
				</strong>, <strong>{this.state.hobbies[3]}</strong>, and <strong>
				{this.state.hobbies[4]}</strong>. As a software developer, my favorite 
				languages are <strong>{this.state.favLanguages[0]} </strong>, <strong>
				{this.state.favLanguages[1]}</strong>, <strong>{this.state.favLanguages[2]}
				</strong>, and <strong>{this.state.favLanguages[3]}</strong> as of recently. 
				Please feel free to look at my portfolio <strong>{this.state.url}</strong>
			</p>
		);
	}
}

export default README;
```

<a href="https://github.com/TrentYetzer">
  <img height="124" align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TrentYetzer&layout=compact&theme=nord&hide=HTML,CSS,Processing,SCSS&langs_count=6" />
</a>
&nbsp;
<a href="https://github.com/TrentYetzer">
  <img height="124" align="center" src="https://github-readme-stats.vercel.app/api?username=TrentYetzer&theme=nord&count_private=true&hide=issues&show_icons=true&line_height=20" alt="Trent's GitHub Stats" />
</a>

1. 	Vladimir Panov
2. 	Phone: 89134563881
	Email: vladimirpanov86@gmail.com
	Telegram: https://t.me/smoothsen
3. 	Constantly developing my skills in IT, 
	really interested in being involved in finding new solutions,	
	I am not afraid of difficulties and do my best in solving the tasks and challenges that have arisen.		
	During this course, I want to improve my frontend skills.
4. 	React, HTML5/CSS, basic level of nodejs, GIT.
5. 	export default class Request {
		_apiBase = `https://someurl/api/v0.1/bounty`

		async getResource(url){
			const res = await fetch(`${this._apiBase}${url}`);

			if(!res.ok) {
				throw new Error(`Could not fetch ${url}, received ${res.status}`)
			}

			return await res.json();
		};

		getDepartment(period) {
			return this.getResource(`/FetchGroupDeptsRequest?period=${period}`);
		}

		getUsersFromDep(period, element) {
			return this.getResource(`/getUsersFromDep?period=${period}&group_dept=${element}`);
		}

		getReportByDep(period, element) {
			return this.getResource(`/getReportByDep?period=${period}&dep=${element}`);
		}
	} 
6. 	Currently at my job I am developing an SPA using React+NodeJS+MsSQL technologies.
7. 	Siberian State University of Telecommunications and Information Sciences
	Engineer, Electronic computers, complexes, systems and networks.
	Online: 
		https://www.udemy.com/share/10208oBksZd19XRHw=/
		https://www.udemy.com/share/101XKiBksZd19XRHw=/
8. 	Intermediate
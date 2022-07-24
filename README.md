<h1 align="center">Hey there <img src="https://user-images.githubusercontent.com/42378118/110234147-e3259600-7f4e-11eb-95be-0c4047144dea.gif" width="20">, I'm Freezy!</h1>
<p align="center">
    <i>Self proclaimed</i> <b>CEO of Procrastination</b> <i>and</i> <b>React and NodeJs Developer</b>
    <br />
    <br />
    <a href="https://hits.seeyoufarm.com/">
        <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FWilly-JL&title_bg=%232D2D2D&count_bg=%2300CC69&icon=github.svg&icon_color=%23E7E7E7&title=Views%20%28Day%20%2F%20All%29&edge_flat=false" />
    </a>
    <a href="https://github.com/freezywt?tab=followers">
        <img src="https://img.shields.io/github/followers/freezywt?labelColor=333333&logoColor=E7E7E7&color=8939FF&label=Followers&logo=github" />
    </a>
    <a href="#">
        <img src="https://img.shields.io/github/stars/freezywt?affiliations=OWNER%2CCOLLABORATOR&labelColor=333333&logoColor=E7E7E7&color=EEAA00&label=Stars&logo=github" />
    </a>
    <br />
    <a href="#">
        <img src="https://img.shields.io/badge/Open_Source-❤-FF0069?style=flat&labelColor=333333&logoColor=E7E7E7">
    </a>
    <a href="#">
        <img src="https://img.shields.io/badge/PRs-Welcome-00CC00?style=flat&labelColor=333333&logoColor=E7E7E7">
    </a>
</p>

<br />

<br />

### index.tsx

```typescript
import profile from './profile.ts'
import api from './api/api.ts'

interface profile{
    username: string;
    fullname: string;
    pronuns: string;
    location: string;
    occupation: string;
    birthday: number;
    age: number;
    hobbies: string;
    interests: string;
    breed: string;
}

export default function Profile({profileInfo}: profile){
    const [ profile, setProfile ] = useState(profileInfo || [])

    return(
        <>
            <div className={styles.profileInfo}>
                {products.map((info) => {
                    return (
                        <Link key={info.id}>
                            <p>{info.name}></p>
                        </Link>
                    )
                })}
            </div>
        </>
    )
}

export const getServerSideProps = canSSRAuth(async (ctx) => {
    const apiClient = setupAPIClient(ctx)
    const ProfileDump = await apiClient.get('/product/all')

    return {
        props: {
            profileInfo: ProfileDump.data
        }
}

```

### apiReturn.json

```json

        "username" = "freezywt",
        "fullname" = "Matheus Fernandes",
        "pronouns" = "he / him",
        "location" = "Brazil",
        "occupation" = "High School Student",
        "birthday" = 2005,
        "age" = 17,
        "hobbies" = { 
            "Coding", 
            "Gaming", 
            "Music", 
            "YouTube"
        }
        "interests" = {
            "Programming", 
            "Linux", 
            "Open Source", 
            "NFT"
        }
        "breed" = "Different"
```

<br />

Languages 💾
------------
![Html5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![css3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)

DataBase 💾
--------
![mongodb](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

Framework 💻
--------
![react](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![nextjs](https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![nodejs](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

Packager Manager 📂
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)
![yarn](https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white)

Clouds ☁️
--------
![aws](https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![replit](https://img.shields.io/badge/replit-667881?style=for-the-badge&logo=replit&logoColor=white)
![heroku](https://img.shields.io/badge/Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white)


Operational System 🛠️
--------
![archlinux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)


<details>
  <summary>:zap: GitHub Stats</summary>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=freezywt&show_icons=true">
</p>
</details>

<details>
  <summary>:zap: GitHub Most Used Languages</summary>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=freezywt&hide=batchfile" />
</p>
</details>

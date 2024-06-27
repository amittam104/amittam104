<div
      ref={gridContainerRef}
      className="grid max-h-[34rem] max-w-[65rem] grid-cols-2 gap-4 lg:grid-cols-12 lg:grid-rows-12"
    >
      <div className="relative col-span-2 flex max-w-full flex-col items-start rounded-3xl border border-slate-300 p-6 pt-8 text-start lg:col-span-8 lg:row-span-6">
        <div className="absolute right-4 top-4 flex items-center gap-3 rounded-md bg-green-100 px-3 py-1 text-sm">
          <img className="static h-6 w-6" src="/circle-svgrepo-com.svg" />
          <p className="static font-medium text-green-900">{job}</p>
        </div>
        <div className="mt-6 pb-6 sm:mt-0">
          <Avatar>
            <AvatarImage
              src={
                avatar
                  ? avatar
                  : `https://upload.wikimedia.org/wikipedia/commons/2/2c/Default_pfp.svg`
              }
            />
            <AvatarFallback>Avatar</AvatarFallback>
          </Avatar>
        </div>
        <h3 className="mb-4 text-4xl font-black">{name}</h3>
        <div className="mb-8 flex flex-col gap-2 sm:flex-row">
          <Badge variant={"primarySkill"}>{primarySkill}</Badge>
          <Badge variant={"secondarySkill"}>{secondarySkill}</Badge>
          <Badge variant={"tertiarySkill"}>{tertiarySkill}</Badge>
        </div>
        <p className="text-2xl">{intro}</p>
      </div>
      <div className="relative col-span-2 flex flex-col items-start justify-end gap-2 rounded-3xl border border-slate-300 p-6 sm:col-span-1 lg:col-span-4 lg:row-span-3">
        <Globe size={28} className="absolute right-4 top-4" />
        <p className="text-slate-500">Reach me out</p>
        <p className="text-2xl font-medium">{portfolio}</p>
      </div>
      <div
        ref={containerRef}
        className="col-span-2 grid grid-cols-4 content-center justify-items-center gap-4 rounded-3xl border border-slate-300 p-4 sm:col-span-1 lg:col-span-4 lg:row-span-3"
      >
        {elements &&
          elements.map((element, index) => (
            <div key={index} className="h-10 w-10">
              {element.outerHTML && (
                <div
                  dangerouslySetInnerHTML={{ __html: element.outerHTML }}
                ></div>
              )}
            </div>
          ))}
      </div>
      <div className="col-span-2 flex flex-col items-start justify-center rounded-3xl border border-slate-300 p-6 text-start md:col-span-1 lg:col-span-3 lg:row-span-6">
        <div className="mb-4 flex h-14 w-14 items-center justify-center rounded-lg border-slate-200 bg-white p-2 shadow">
          <img
            src={
              projectLogo
                ? projectLogo
                : `https://www.amittambulkar.com/logo.svg`
            }
            alt="project logo"
          />
        </div>
        <h4 className="mb-6 text-lg font-semibold">{projectName}</h4>
        <p className="text-sm">
          {projectIntro
            ? projectIntro
            : `Add one line intro for your capstone project here. Showcase the features in few simple words.`}
        </p>
      </div>
      <div className="col-span-2 flex items-center justify-center rounded-3xl border border-slate-300 p-4 md:col-span-1 lg:col-span-4 lg:row-span-6">
        <img
          className="max-h-full w-auto rounded-lg border-[3px] border-slate-800 shadow-xl"
          src={projectImage ? projectImage : `/BentoHubSnap.png`}
          alt="bento hub app screenshot"
        />
      </div>
      <div className="col-span-2 flex items-center justify-center overflow-hidden rounded-3xl border border-slate-300 p-6 md:col-span-1 lg:col-span-5 lg:row-span-6">
        <img
          className="max-h-full w-auto rounded-lg border-[3px] border-slate-800 shadow-xl"
          src={projectImage2 ? projectImage2 : `/portfolio.png`}
          alt="Portfolio screenshot"
        />
      </div>
    </div>


#  Amit Tambulkar

**`A frontend developer focused on building products that people can use.`**

I’m a frontend web developer focused on building real-world applications that people can use. Although my programming journey began with Python, where I worked on my problem-solving skills and built some projects (including a web scraper), my current focus is entirely on front-end development. Recently, I’ve started building full-stack projects while using backend-as-a-service solutions.

- 🔭 I’m currently working on [Forkify](https://github.com/amittam104/Forkify)

- 👨‍💻 All of my projects are available at [https://github.com/amittam104](https://github.com/amittam104)

- 📫 How to reach me **amittambulkar104@gmail.com**

#

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://twitter.com/attambulkar" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="attambulkar" height="30" width="40" /></a>
<a href="https://linkedin.com/in/amittambulkar" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="amittambulkar" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://appwrite.io" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/appwriteio/appwriteio-icon.svg" alt="appwrite" width="40" height="40"/> </a> <a href="https://babeljs.io/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/babeljs/babeljs-icon.svg" alt="babel" width="40" height="40"/> </a> <a href="https://www.chartjs.org" target="_blank" rel="noreferrer"> <img src="https://www.chartjs.org/media/logo-title.svg" alt="chartjs" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.adobe.com/in/products/illustrator.html" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/adobe_illustrator/adobe_illustrator-icon.svg" alt="illustrator" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" width="40" height="40"/> </a> </p>

<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=amittam104&show_icons=true&locale=en&layout=compact" alt="amittam104" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=amittam104&" alt="amittam104" /></p>

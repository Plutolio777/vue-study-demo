# 使用VueCli来构建项目

## 安装

可以使用npm和yarn进行脚手架的安装(最好进行全局安装)

~~~bash
yarn global add @vue/cli
# 或
npm install -g @vue/cli
~~~

安装完成之后会再命令行添加vue指令，通过以下指令可以查看是否创建成功

~~~bash
vue -v
2.9.6
~~~

~~~bash
vue create `项目名称`
~~~

## 利用vite对vue项目进行打包

我们可以使用npm

~~~bash
npm 6.x
npm init vite@latest <project-name> --template vue

npm 7+
npm init vite@latest <project-name> -- --template vue

cd <project-name>
npm install
npm run dev
~~~

使用yarn

~~~bash
yarn create vite <project-name> --template vue
yarn
yarn dev
~~~

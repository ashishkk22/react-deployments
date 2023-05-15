
# React application deployment. 
React practical deployment with different environment. 

Vite uses dotenv to load additional environment variables from the following files in your environment directory:
```
.env                # loaded in all cases
.env.local          # loaded in all cases, ignored by git
.env.[mode]         # only loaded in specified mode
.env.[mode].local   # only loaded in specified mode, ignored by git
```

To pass the different .env we can run the below command as per the required build.
```
vite --mode development                # loaded the variables from the .env.development
tsc && vite build --mode staging       # loaded the variable from the .env.staging
tsc && vite build --mode production    # loaded the variable from the .env.production
```

### Practical 2

https://todo-react-ts-ui.netlify.app/

### Practical 3

https://todo-react-ts-22.netlify.app/

### Practical 4

https://user-list-ui-f1.netlify.app/

### Practical 5 server

https://user-list-server-node-ak.vercel.app (express + mongodb)

### Practical 5 client

https://user-list-ui-f2.netlify.app/

### Practical 7 client + server 

https://user-management-7.onrender.com/ (react + express + mongodb + imageKit)


# Angular 5 with Spring Boot Template

Spring Boot 1.5.9 + Angular 5 Universal

## Front

- `npm install -S @angular/platform-server`
- `npm install -D ts-loader webpack-node-externals npm-run-all`
- `npm install`
- `npm run build`
- `node dist/server.js`

Navigate to `http://localhost:4200/`.

## Back

Run `cloud.defaulty.TemplateApplication` as Spring Boot app.

## Others

Java part using Lombok plugin. If you run project in Intellij Idea you may need enable annotation processing in Build->Compiler->Annotation Processor.
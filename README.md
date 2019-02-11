## Welcome to my page!

![LX470](https://puu.sh/CKqm4/b86af29c8b.jpg)

I am a Biology major/CS minor student at BSU. I will be graduating in May 2019. I love programming and the outdoors, and want a career that combines the two. My dream job is building hardware and software solutions for biological research and deploying it in the field.

### Here is a small snippet of code from one of my projects to test the syntax highlighting
```Java
try (BufferedReader br = new BufferedReader(new InputStreamReader(p.getInputStream()))) {

  boolean found = true;
  for (input = br.readLine(); input != null && found; input = br.readLine()) {
    if (input.contains("[")) {
      int posBracket = input.indexOf('[');
      int posPercent = input.indexOf('%', posBracket + 1);
      inputParsed = input.substring(posBracket + 1, posPercent);
      volInitParsed = Integer.parseInt(inputParsed);
      found = false;
    }
  }
}
```

jvm_binary(name = 'main',
  source = 'HelloWorld.java',
  dependencies = [
    ':test-lib'
  ],
  main = 'sunjoo.HelloWorld',
  basename = 'sunjoo',
)


java_library(name = 'test-lib', 
    sources=globs('Test.java'),
    platform='java7',
)

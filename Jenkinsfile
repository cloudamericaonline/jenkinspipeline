stage 'test'
node {
 echo "Hello from Jenkins" 
}

stage 'test2'
parallel 'test2-a' : {
 node {
 echo "Hello from test2-a"
 }},
 'test2-b' : {
  node {
 echo "Hello from test2-a"
 }}

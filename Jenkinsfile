def configMap = [
    project: "roboshop",
    component: "catalogue"
]

echo "Triggering the Library Pipeline"

if (env.BRANCH_NAME.equalsIgnoreCase('main')) {
    echo "Checking later"
}
else{
    nodeJSEKSPipeline(configMap)
}
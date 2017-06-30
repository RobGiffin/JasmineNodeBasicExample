install jasmine for node

npm install jasmine-node -g

then from command prompt

jasmine-node
(will show all options)


(will run all specs in the /spec folder)
jasmine-node spec

(spec files should be named)
calculator-spec.js

jasmine-node spec --autotest
(auto run test)

jasmine-node spec --autotest --watch .
(auto run test and watch for changes to files in the project)


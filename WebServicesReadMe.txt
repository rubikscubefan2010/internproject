/*
 * http://winksplayground.x10host.com/allprojectsservice
 * Returns a json encoded list of all projects.
 * Sample Response = [{"id":"13","projectName":"Bench"}, {"id":"14","projectName":"Bench2"}, {"id":"15","projectName":"Bench3"}]
 *
*/
function getAvailableProjects()



/*
 * http://winksplayground.x10host.com/currentprojectservice
 * Returns a json encoded object of any project currently being timed.
 * Returns Null or empty if there is no project currently being timed.
 * Sample Response = {"id":"13","projectName":"Bench"}
 *
*/
function getRunningProject()



/*
 * http://winksplayground.x10host.com/starttimeservice
 * Receives POST variable of projectId and records the start time in the database.
 * Variable should be sent as a parameter with an application/x-www-form-urlencoded Http header.
 * Returns a json encoded string of the project id and the time that was recorded.
 * Sample Response = {"id":"13","time":"2016-12-22 10:48:6"}
*/
function postStartTime()



/*
 * http://winksplayground.x10host.com/endtimeservice
 * Receives POST variable of projectId and records the end time in the database.
 * Variable should be sent as a parameter with an application/x-www-form-urlencoded Http header.
 * Returns a json encoded string of the project id and the time that was recorded.
 * Sample Response = {"id":"13","time":"2016-12-22 10:48:6"}
*/
function postEndTime()


/*
 * http://winksplayground.x10host.com/imageservice
 * Receives POST variable of and image and processes it on the server.
 * Variable should be sent as a parameter with an application/x-www-form-urlencoded or multipart/form-data Http header.
 * Returns a string with a message indicating success or failure.
 * Sample Response = "The file myImage.png has been uploaded."
*/
function imageUpload()

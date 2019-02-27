# Client Meeting Minutes 

### First Meeting: 9/20/18
1. kyle has 2 kids and is not available in the evenings.
2. He went to Ball State and majored in Computer Science.
3. He created the Traveler App as a consumer based application for the architecture college. He eventually purchased this app from the university.
4. Know or learn how to parse different file types.
5. He currently manages the database himself once a month for a few businesses in Muncie.
6. Have an Import process to accept different types of data.
7. We shouldn’t need to deal with login credentials, but they use Google for the login.
8. We are making a website/app to use the database Kyle has already created. 
9. Sync external things into the app soley, not the other way around.
10. There should be a free version of azure, although it may be slower.
11. Monday October 15th at 10 am NEXT MEETING


### Second Meeting: 10/15/18
1. Schema Information  
Updated by Tours/Events, not visible but still stored after Date  
No automation done by us  
No data Deleted  
2. Tour Details  
Flags that identify users who can see certain Tours/Events  
Talked about collaborators, but will come back to in later meetings
3. Manually entering information
Search capabilities  
Usually grabbed by google maps(Long/Lat) what we will use  
No limits on tours or events available for creation  
4. Marker creation
Like google in style  
Markers should be stitched together after marker information is provided  
Possibly customer preplans KML file on google (pre set tour)  
Import KML file that we convert to fit application style
5. Visual  
More content view than map, but both are accessible  
A lot is based on previous tours and events, having that access as well as map and tour creation visible   
Customer if having created a tour before, has generic information populated to entry, a lot of times information by customer   is reused(pictures)  
6. Avoid using PathPoint**  
KML import would convert to a geo json file for mapping
7. Monday November 12th at 10am NEXT MEETING


### Third Meeting: 11/28/18
1. Showed Kyle our prototype/UML.
2. Some changes to prototype include, Locations is known as Places.
3. Events are more of a list structure because of how few there are.
4. Order (Tours, Places, Events) and a search feature is needed.
5. VISUAL STUDIO INFORMATION.
6. Look up mVC when learning the structure of the visual studio.
7. When installing things like NuGet packages remember to find the source(Author).
8. 'Nuton' isn't the correct name but get that software for Json files from NuGet.
9. Stick with the azure side fo the database connection for testing.
10. Kyle is sending us packages and stored procedures.
11. OTHER INFORMATION.
12. Category is a huge key factor for tours while events are more just connected to the business itself.
13. Item to organization connection is the main connection that holds everything together (review Domain model)
14. TO DO.
15. Might need to create update procedures and others that kyle doesn't have already.
16. Places have categories assigned to them, there is always a default place.
17. Need something to manage places --> tours.
18. Items --> organization.
19. Map view focus is mainly on Places only.
20. Featured items(tour editing) - being able to select what places they want to feature which then relates to the organization items.
21. Kyle will send us background information on the tours involving the path.
22. Detailed split view, not just one view.
23. Kyle should be sending us 4 files after meeting.
24. Next meeting not scheduled because of winter break.

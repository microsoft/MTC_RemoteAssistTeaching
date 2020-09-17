BOM
	- HD Video Capture: https://www.amazon.com/Capture-Broadcast-Streaming-Grabber-Converter/dp/B0779ZJZX3
	- OBS Studio (Open Broadcaster Software, free and open source): https://obsproject.com/
	- Sample scene resources: Remote_Assist.json

Setup
Presenter
	1. HoloLens with Remote Assist installed
	2. PC configured so that it acts as a "Miracast" receiver
	3. Confirm that the HoloLens will connect and share its display with the PC: https://docs.microsoft.com/en-us/hololens/holographic-photos-and-videos (Go to the section "Streaming video with Miracast)
	4. Teams installed
	5. Team meeting schedule with the audience invited (This will be the meeting that guests/students attend to watch the presenter and helpers session)
	6. If you plan to use Holograms or other content like webpages, drawings etc, place those in the space in which you plan to present. (This prestaging and its critical to ensure you have a good experience)

Helper
	1. The OBS Projection monitor resolution should be set to 1920x1080
	2. Download the sample scene resources Remote_Assist.json
	3. Install OBS on PRODLAP
		a. Import the downloaded sample Scene Collection
		b. Switch to the Remote Assist Scene Collection
		
		
		c. Update the HD Video Capture Source in the Helper Scene to use your device
	4. Have reference materials ready to go on DEMOLAP
		a. TODO - These are the materials that will help the "presenter" solve their problem or in the case of a teaching scenario re-enforce the content being presented (See the sample video) 

Demo
Presenter
	1. Start Teams on the PRODLAP
	2. Join the meeting on the PRODLAP - Do this well in advance of the actual start time of the meeting (15 mins is a good start as it allows you to ensure things are connected and working.)
	3. Begin streaming the HoloLens video to the PRODLAP using Miracast.
	4. Share the PRODLAP screen in the Teams meeting 
	5. Start the Remote Assist from inside HoloLens calling the "Helper"
	6. Begin your demonstration. 

Alternative Presenter
You could also create the "Presenter" view using the documentation for setting up the "Helper" device DEMOLAP. In this case you'd need 2 laptops. One to host the HoloLens Miracast stream and the other to host the Teams meeting. You would then use the HD Video Capture plug in to stream the HoloLens experience on to the PRODLAP.  
	
	
	

Helper
	1. Start Microsoft Teams on DEMOLAP
	2. Plug in HD Video Capture to DEMOLAP and PRODLAP
	3. Start OBS on PRODLAP
		a. Select the Helper scene
		b. Right-click on the scene display -> Fullscreen Projector (Preview) -> [your external monitor]
	4. Start Microsoft Teams on PRODLAP
	5. Join the Customer Teams Meeting ON PRODLAP
		a. Share [your external monitor] screen in the Teams Meeting
	6. Accept call from Presenter on DEMOLAP
	7. TODO: Annotate in Remote Assist on DEMOLAP
	8. TODO: Upload file in Remote Assist on DEMOLAP

# ImagePicker

	// Set "imageSourceType" - .camera OR .photoLibrary
	
	let vc = UIViewController()

 	ImagePicker.openImagePickerController(viewController: vc, imageSourceType: .photoLibrary , completion: { (image) in
 
   		 print(image)
   		 // DO STUFF HERE WITH SELECTED IMAGE
                
	 }, canceled: { (isCanceled) in
		print("Image picker : \(isCanceled)")
 	}, error: { (message) in
		print(message)
	 })
 

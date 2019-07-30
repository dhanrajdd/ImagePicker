# ImagePicker



 ImagePicker.openImagePickerController(viewController: self, imageSourceType: index == 0 ? .photoLibrary : .camera, completion: { (image) in
 
                
    print(image)
    // DO STUFF HERE WITH SELECTED IMAGE
                
 }, canceled: { (isCanceled) in
    
		print("Image picker : \(isCanceled)")
    
 }, error: { (message) in
    
		print(message)
		
 })
 

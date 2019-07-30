# ImagePicker

// Set "imageSourceType" - .camera OR .photoLibrary

 ImagePicker.openImagePickerController(viewController: self, imageSourceType: .photoLibrary , completion: { (image) in
 
                
    print(image)
    // DO STUFF HERE WITH SELECTED IMAGE
                
 }, canceled: { (isCanceled) in
    
		print("Image picker : \(isCanceled)")
    
 }, error: { (message) in
    
		print(message)
		
 })
 

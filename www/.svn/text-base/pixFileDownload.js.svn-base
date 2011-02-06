//
//  pixFileDownload.js
//  FileDownLoadApp
//
//  Created by Aaron saunders on 9/8/10.
//  Copyright 2010 __MyCompanyName__. All rights reserved.
//

function PixFileDownload() {
}

PixFileDownload.prototype.downloadFile = function(url,destFileName) {
    PhoneGap.exec("PixFileDownload.downloadFile", url,destFileName);
};

PhoneGap.addConstructor(function() {
	window.fileDownloadMgr = new PixFileDownload();
});


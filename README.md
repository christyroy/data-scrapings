{
   "@Ignorable": "sap sap2010",
   "@Class": "data_scraping",
   "@VisualBasic.Settings": "{x:Null}",
   "@VirtualizedContainerService.HintSize": "680,1612",
   "@WorkflowViewState.IdRef": "data_scraping_1",
   "TextExpression.NamespacesForImplementation": {
      "Collection": {
         "@TypeArguments": "x:String",
         "String": [
            "System.Activities",
            "System.Activities.Statements",
            "System.Activities.Expressions",
            "System.Activities.Validation",
            "System.Activities.XamlIntegration",
            "Microsoft.VisualBasic",
            "Microsoft.VisualBasic.Activities",
            "System",
            "System.Collections",
            "System.Collections.Generic",
            "System.Data",
            "System.Diagnostics",
            "System.Drawing",
            "System.IO",
            "System.Linq",
            "System.Net.Mail",
            "System.Xml",
            "System.Xml.Linq",
            "UiPath.Core",
            "UiPath.Core.Activities",
            "System.Windows.Markup",
            "System.Xml.Serialization"
         ]
      }
   },
   "TextExpression.ReferencesForImplementation": {
      "Collection": {
         "@TypeArguments": "AssemblyReference",
         "AssemblyReference": [
            "System.Activities",
            "Microsoft.VisualBasic",
            "mscorlib",
            "System.Data",
            "System.Data.DataSetExtensions",
            "System",
            "System.Drawing",
            "System.Core",
            "System.Xml",
            "System.Xml.Linq",
            "PresentationFramework",
            "WindowsBase",
            "PresentationCore",
            "System.Xaml",
            "UiPath.System.Activities",
            "UiPath.UiAutomation.Activities",
            "UiPath.System.Activities.Design"
         ]
      }
   },
   "Sequence": {
      "@DisplayName": "data_scraping",
      "@VirtualizedContainerService.HintSize": "527,1407",
      "@WorkflowViewState.IdRef": "Sequence_1",
      "WorkflowViewStateService.ViewState": {
         "Dictionary": {
            "@TypeArguments": "x:String, x:Object",
            "Boolean": {
               "@Key": "IsExpanded",
               "#text": "True"
            }
         }
      },
      "OpenBrowser": {
         "@BrowserType": "{x:Null}",
         "@CommunicationMethod": "{x:Null}",
         "@Hidden": "{x:Null}",
         "@NewSession": "{x:Null}",
         "@Private": "{x:Null}",
         "@UiBrowser": "{x:Null}",
         "@DisplayName": "Open Browser",
         "@VirtualizedContainerService.HintSize": "485,647",
         "@WorkflowViewState.IdRef": "OpenBrowser_1",
         "@Url": "https://www.google.com/#spf=1597379951275",
         "OpenBrowser.Body": {
            "ActivityAction": {
               "@TypeArguments": "x:Object",
               "ActivityAction.Argument": {
                  "DelegateInArgument": {
                     "@TypeArguments": "x:Object",
                     "@Name": "ContextTarget"
                  }
               },
               "Sequence": {
                  "@DisplayName": "Do",
                  "@VirtualizedContainerService.HintSize": "376,546",
                  "@WorkflowViewState.IdRef": "Sequence_2",
                  "WorkflowViewStateService.ViewState": {
                     "Dictionary": {
                        "@TypeArguments": "x:String, x:Object",
                        "Boolean": {
                           "@Key": "IsExpanded",
                           "#text": "True"
                        }
                     }
                  },
                  "TypeInto": [
                     {
                        "@AlterIfDisabled": "{x:Null}",
                        "@DelayBetweenKeys": "{x:Null}",
                        "@EmptyField": "{x:Null}",
                        "@SendWindowMessages": "{x:Null}",
                        "@SimulateType": "{x:Null}",
                        "@Activate": "True",
                        "@ClickBeforeTyping": "True",
                        "@DelayBefore": "1000",
                        "@DelayMS": "1000",
                        "@DisplayName": "Type Into 'INPUT'",
                        "@VirtualizedContainerService.HintSize": "334,134",
                        "@WorkflowViewState.IdRef": "TypeInto_1",
                        "@Text": "https://www.amazon.in/[k(enter)]",
                        "TypeInto.Target": {
                           "Target": {
                              "@ClippingRegion": "{x:Null}",
                              "@Element": "{x:Null}",
                              "@Id": "4aa99366-63d7-450c-ae66-8396761094fe",
                              "@InformativeScreenshot": "1ccdc97e9eea8f86611d20f616ec7949",
                              "@Selector": "<webctrl name='q' tag='INPUT' />",
                              "Target.TimeoutMS": {
                                 "InArgument": {
                                    "@TypeArguments": "x:Int32"
                                 }
                              },
                              "Target.WaitForReady": {
                                 "InArgument": {
                                    "@TypeArguments": "ui:WaitForReady"
                                 }
                              }
                           }
                        }
                     },
                     {
                        "@AlterIfDisabled": "{x:Null}",
                        "@DelayBetweenKeys": "{x:Null}",
                        "@EmptyField": "{x:Null}",
                        "@SendWindowMessages": "{x:Null}",
                        "@SimulateType": "{x:Null}",
                        "@Activate": "True",
                        "@ClickBeforeTyping": "True",
                        "@DelayBefore": "1000",
                        "@DelayMS": "1000",
                        "@DisplayName": "Type Into 'INPUT  twotabsearchtext...'",
                        "@VirtualizedContainerService.HintSize": "334,134",
                        "@WorkflowViewState.IdRef": "TypeInto_4",
                        "@Text": "men sunglasses[k(enter)]",
                        "TypeInto.Target": {
                           "Target": {
                              "@ClippingRegion": "{x:Null}",
                              "@Element": "{x:Null}",
                              "@Id": "b9e33699-519f-4fc6-9cb7-677aee8cf014",
                              "@InformativeScreenshot": "5a5ce2834ed5f642c3bb67d0870be575",
                              "@Selector": "<webctrl id='twotabsearchtextbox' tag='INPUT' />",
                              "Target.TimeoutMS": {
                                 "InArgument": {
                                    "@TypeArguments": "x:Int32"
                                 }
                              },
                              "Target.WaitForReady": {
                                 "InArgument": {
                                    "@TypeArguments": "ui:WaitForReady"
                                 }
                              }
                           }
                        }
                     }
                  ],
                  "Click": {
                     "@AlterIfDisabled": "{x:Null}",
                     "@DelayBefore": "{x:Null}",
                     "@DelayMS": "{x:Null}",
                     "@SendWindowMessages": "{x:Null}",
                     "@SimulateClick": "{x:Null}",
                     "@ClickType": "CLICK_SINGLE",
                     "@DisplayName": "Click 'H3'",
                     "@VirtualizedContainerService.HintSize": "334,106",
                     "@WorkflowViewState.IdRef": "Click_2",
                     "@KeyModifiers": "None",
                     "@MouseButton": "BTN_LEFT",
                     "Click.CursorPosition": {
                        "CursorPosition": {
                           "@Position": "Center",
                           "CursorPosition.OffsetX": {
                              "InArgument": {
                                 "@TypeArguments": "x:Int32"
                              }
                           },
                           "CursorPosition.OffsetY": {
                              "InArgument": {
                                 "@TypeArguments": "x:Int32"
                              }
                           }
                        }
                     },
                     "Click.Target": {
                        "Target": {
                           "@ClippingRegion": "{x:Null}",
                           "@Element": "{x:Null}",
                           "@Id": "a0896ab3-89c5-4443-af92-c71ef23c0918",
                           "@InformativeScreenshot": "75b2eaf6990dc5c181aa29307df44ce4",
                           "@Selector": "<webctrl aaname='Amazon.in' tag='H3' />",
                           "Target.TimeoutMS": {
                              "InArgument": {
                                 "@TypeArguments": "x:Int32"
                              }
                           },
                           "Target.WaitForReady": {
                              "InArgument": {
                                 "@TypeArguments": "ui:WaitForReady"
                              }
                           }
                        }
                     }
                  }
               }
            }
         }
      },
      "Sequence": {
         "@DisplayName": "Data Scraping",
         "@VirtualizedContainerService.HintSize": "485,628",
         "@WorkflowViewState.IdRef": "Sequence_11",
         "Sequence.Variables": {
            "Variable": {
               "@TypeArguments": "sd:DataTable",
               "@Default": "[New System.Data.DataTable]",
               "@Name": "ExtractDataTable"
            }
         },
         "WorkflowViewStateService.ViewState": {
            "Dictionary": {
               "@TypeArguments": "x:String, x:Object",
               "Boolean": {
                  "@Key": "IsExpanded",
                  "#text": "True"
               }
            }
         },
         "BrowserScope": {
            "@Browser": "{x:Null}",
            "@SearchScope": "{x:Null}",
            "@TimeoutMS": "{x:Null}",
            "@UiBrowser": "{x:Null}",
            "@BrowserType": "IE",
            "@DisplayName": "Attach Browser 'Amazoninm Page'",
            "@VirtualizedContainerService.HintSize": "434,344",
            "@WorkflowViewState.IdRef": "BrowserScope_4",
            "@InformativeScreenshot": "633b216e8f35a1eb7f458184134366aa",
            "@Selector": "<html title='Amazon.in : men sunglasses' />",
            "BrowserScope.Body": {
               "ActivityAction": {
                  "@TypeArguments": "x:Object",
                  "ActivityAction.Argument": {
                     "DelegateInArgument": {
                        "@TypeArguments": "x:Object",
                        "@Name": "ContextTarget"
                     }
                  },
                  "Sequence": {
                     "@DisplayName": "Do",
                     "@VirtualizedContainerService.HintSize": "376,198",
                     "@WorkflowViewState.IdRef": "Sequence_10",
                     "WorkflowViewStateService.ViewState": {
                        "Dictionary": {
                           "@TypeArguments": "x:String, x:Object",
                           "Boolean": {
                              "@Key": "IsExpanded",
                              "#text": "True"
                           }
                        }
                     },
                     "ExtractData": {
                        "@DelayBetweenPagesMS": "{x:Null}",
                        "@ContinueOnError": "True",
                        "@DataTable": "[ExtractDataTable]",
                        "@DisplayName": "Extract Structured Data 'DIV  search'",
                        "@ExtractMetadata": "<extract><row exact='1'><webctrl class='s-desktop-width-max s-desktop-content sg-row' tag='div' idx='1' /><webctrl class='sg-col-20-of-24 sg-col-28-of-32 sg-col-16-of-20 sg-col sg-col-32-of-36 sg-col-8-of-12 sg-col-12-of-16 sg-col-24-of-28' tag='div' idx='1' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='rush-component s-latency-cf-section' tag='span' idx='1' /><webctrl class='s-main-slot s-result-list s-search-results sg-row' tag='div' idx='1' /><webctrl class='sg-col-4-of-24 sg-col-4-of-12 sg-col-4-of-36 s-result-item s-asin sg-col-4-of-28 sg-col-4-of-16 AdHolder sg-col sg-col-4-of-20 sg-col-4-of-32' tag='div' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='celwidget slot=MAIN template=SEARCH_RESULTS widgetId=search-results' tag='span' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='s-expand-height s-include-content-margin s-latency-cf-section' tag='div' idx='1' /><webctrl class='a-section a-spacing-medium a-text-center' tag='div' idx='1' /><\/row><column attr='text' name='Title' exact='1' attr2='href' name2='URL'><webctrl class='s-desktop-width-max s-desktop-content sg-row' tag='div' idx='1' /><webctrl class='sg-col-20-of-24 sg-col-28-of-32 sg-col-16-of-20 sg-col sg-col-32-of-36 sg-col-8-of-12 sg-col-12-of-16 sg-col-24-of-28' tag='div' idx='1' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='rush-component s-latency-cf-section' tag='span' idx='1' /><webctrl class='s-main-slot s-result-list s-search-results sg-row' tag='div' idx='1' /><webctrl class='sg-col-4-of-24 sg-col-4-of-12 sg-col-4-of-36 s-result-item s-asin sg-col-4-of-28 sg-col-4-of-16 AdHolder sg-col sg-col-4-of-20 sg-col-4-of-32' tag='div' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='celwidget slot=MAIN template=SEARCH_RESULTS widgetId=search-results' tag='span' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='s-expand-height s-include-content-margin s-latency-cf-section' tag='div' idx='1' /><webctrl class='a-section a-spacing-medium a-text-center' tag='div' idx='1' /><webctrl class='a-section a-spacing-none a-spacing-top-small' tag='div' idx='1' /><webctrl class='a-size-mini a-spacing-none a-color-base s-line-clamp-2' tag='h2' idx='1' /><webctrl class='a-link-normal a-text-normal' tag='a' idx='1' /><webctrl class='a-size-base-plus a-color-base a-text-normal' tag='span' idx='1' /><\/column><column attr='text' name='Price' exact='1'><webctrl class='s-desktop-width-max s-desktop-content sg-row' tag='div' idx='1' /><webctrl class='sg-col-20-of-24 sg-col-28-of-32 sg-col-16-of-20 sg-col sg-col-32-of-36 sg-col-8-of-12 sg-col-12-of-16 sg-col-24-of-28' tag='div' idx='1' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='rush-component s-latency-cf-section' tag='span' idx='1' /><webctrl class='s-main-slot s-result-list s-search-results sg-row' tag='div' idx='1' /><webctrl class='sg-col-4-of-24 sg-col-4-of-12 sg-col-4-of-36 s-result-item s-asin sg-col-4-of-28 sg-col-4-of-16 AdHolder sg-col sg-col-4-of-20 sg-col-4-of-32' tag='div' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='celwidget slot=MAIN template=SEARCH_RESULTS widgetId=search-results' tag='span' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='s-expand-height s-include-content-margin s-latency-cf-section' tag='div' idx='1' /><webctrl class='a-section a-spacing-medium a-text-center' tag='div' idx='1' /><webctrl class='a-section a-spacing-none a-spacing-top-small' tag='div' idx='2' /><webctrl class='a-row a-size-base a-color-base' tag='div' idx='1' /><webctrl class='a-row' tag='div' idx='1' /><webctrl class='a-size-base a-link-normal s-no-hover a-text-normal' tag='a' idx='1' /><webctrl class='a-price' tag='span' idx='1' /><webctrl tag='span' idx='2' /><webctrl class='a-price-whole' tag='span' idx='1' /><\/column><column attr='text' name='Rating' exact='1'><webctrl class='s-desktop-width-max s-desktop-content sg-row' tag='div' idx='1' /><webctrl class='sg-col-20-of-24 sg-col-28-of-32 sg-col-16-of-20 sg-col sg-col-32-of-36 sg-col-8-of-12 sg-col-12-of-16 sg-col-24-of-28' tag='div' idx='1' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='rush-component s-latency-cf-section' tag='span' idx='1' /><webctrl class='s-main-slot s-result-list s-search-results sg-row' tag='div' idx='1' /><webctrl class='sg-col-4-of-24 sg-col-4-of-12 sg-col-4-of-36 s-result-item s-asin sg-col-4-of-28 sg-col-4-of-16 AdHolder sg-col sg-col-4-of-20 sg-col-4-of-32' tag='div' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='celwidget slot=MAIN template=SEARCH_RESULTS widgetId=search-results' tag='span' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='s-expand-height s-include-content-margin s-latency-cf-section' tag='div' idx='1' /><webctrl class='a-section a-spacing-medium a-text-center' tag='div' idx='1' /><webctrl class='a-section a-spacing-none a-spacing-top-micro' tag='div' idx='1' /><webctrl class='a-row a-size-small' tag='div' idx='1' /><webctrl tag='span' idx='1' /><webctrl class='a-declarative' tag='span' idx='1' /><webctrl class='a-popover-trigger a-declarative' tag='a' idx='1' /><webctrl tag='i' /><webctrl class='a-icon-alt' tag='span' idx='1' /><\/column><column attr='src' name='Image' exact='1'><webctrl class='s-desktop-width-max s-desktop-content sg-row' tag='div' idx='1' /><webctrl class='sg-col-20-of-24 sg-col-28-of-32 sg-col-16-of-20 sg-col sg-col-32-of-36 sg-col-8-of-12 sg-col-12-of-16 sg-col-24-of-28' tag='div' idx='1' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='rush-component s-latency-cf-section' tag='span' idx='1' /><webctrl class='s-main-slot s-result-list s-search-results sg-row' tag='div' idx='1' /><webctrl class='sg-col-4-of-24 sg-col-4-of-12 sg-col-4-of-36 s-result-item s-asin sg-col-4-of-28 sg-col-4-of-16 AdHolder sg-col sg-col-4-of-20 sg-col-4-of-32' tag='div' /><webctrl class='sg-col-inner' tag='div' idx='1' /><webctrl class='celwidget slot=MAIN template=SEARCH_RESULTS widgetId=search-results' tag='span' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='rush-component s-expand-height' tag='div' idx='1' /><webctrl class='s-expand-height s-include-content-margin s-latency-cf-section' tag='div' idx='1' /><webctrl class='a-section a-spacing-medium a-text-center' tag='div' idx='1' /><webctrl class='a-section a-spacing-none s-image-overlay-black' tag='div' idx='1' /><webctrl class='s-image-overlay-white-semitransparent' tag='div' idx='1' /><webctrl class='rush-component' tag='span' idx='1' /><webctrl class='a-link-normal s-no-outline' tag='a' idx='1' /><webctrl class='a-section aok-relative s-image-tall-aspect' tag='div' idx='1' /><webctrl class='s-image' tag='img' idx='1' /><\/column><\/extract>",
                        "@VirtualizedContainerService.HintSize": "334,106",
                        "@WorkflowViewState.IdRef": "ExtractData_4",
                        "@MaxNumberOfResults": "200",
                        "@NextLinkSelector": "<webctrl aaname='Next→' parentid='search' tag='A' />",
                        "@SimulateClick": "True",
                        "ExtractData.Target": {
                           "Target": {
                              "@ClippingRegion": "{x:Null}",
                              "@Element": "{x:Null}",
                              "@Id": "a9aedc1a-a9de-4f0a-a134-760c5bda30ba",
                              "@InformativeScreenshot": "d4c324b256251613381c38aa4cb1e581",
                              "@Selector": "<webctrl id='search' tag='DIV' />",
                              "@WaitForReady": "COMPLETE",
                              "Target.TimeoutMS": {
                                 "InArgument": {
                                    "@TypeArguments": "x:Int32"
                                 }
                              }
                           }
                        }
                     }
                  }
               }
            }
         },
         "WriteCsvFile": {
            "@Encoding": "{x:Null}",
            "@AddHeaders": "True",
            "@DataTable": "[ExtractDataTable]",
            "@Delimitator": "Comma",
            "@DisplayName": "Write CSV",
            "@FilePath": "C:\\Users\\Rohit\\Desktop\\results.csv",
            "@VirtualizedContainerService.HintSize": "434,152",
            "@WorkflowViewState.IdRef": "WriteCsvFile_3"
         }
      }
   }
}
